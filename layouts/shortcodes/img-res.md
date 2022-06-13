{{ $src := (.Get 0) }}
{{ $options := .Get 1 }}
{{ with .Site.GetPage "section" "media" }}
  {{ $original := .Resources.GetByPrefix  $src }}
  {{ with ($original.Resize $options) }}
  <img src="{{ .RelPermalink }}" width="{{ .Width }}" height="{{ .Height }}">
  {{ end }} 
{{ end }}
