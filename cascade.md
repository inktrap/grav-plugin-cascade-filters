
# is the config path correct?

- how are you supposed to overwrite a plugin config? this seems correct:
default config is under: [love@arcturus]~/html% user/plugins/cascade-filters.yaml 
server generated config is under: [love@arcturus]~/html% user/config/plugins/cascade-filters.yaml 


# todo

- plugin has incorrect default config (string instead of array for select_pages)
- list has li items in default theme
- multiple taxonomy labels and items are messed up (use taxonomy plugin)
- "if plugin enabled"-setting does not work in twig


# done

- i am sorting taxonomies to make their order predictable (uberspace-local difference). this is not optimal, a custom ordering would be optimal.
- add config on localhost
- clicking a tag does nothing: wrong url generated if {{url}} is / in genQueryUrl <https://github.com/ash0080/grav-plugin-cascade-filters/blob/f1c460e0348b24433084ad37881c32391819cc26/templates/partials/cascade-filters.html.twig>

