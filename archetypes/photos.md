+++
type = "gallery"
title = "{{ replace .File.ContentBaseName '-' ' ' | title }}"
date = {{ dateFormat "2006-01-02" .Date }}
image = "{{ .File.ContentBaseName }}.jpg"
categories = []
+++