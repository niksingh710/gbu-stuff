# General college stuff 

> **(Ignore if you are not in GBU university)**

### Timetabl

To run timetable make sure you have access to `bash`.

**Packages required:** `wkhtmltopdf`
**Optional:** `zathura`

```bash
curl -s "https://raw.githubusercontent.com/niksingh710/gbu-stuff/master/timetable.sh" | bash -s -- --pdf-viewer "firefox"
```

To use `zathura` as pdf viewer, remove `--pdf-viewer "firefox"` from above command.
