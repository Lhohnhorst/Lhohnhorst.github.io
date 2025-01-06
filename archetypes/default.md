+++
date = '{{ $t := "13 Dez 2024" }}
        {{ time.Format "2 Jan 2006" $t }} → 13 Dez 2024'
draft = true
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
+++
