# Regex
Collection of useful regex

# ngx-translate
Auto inject translate pipe in the html tags and placeholders
1. change tag

     > find: `(?<=>)([\w\s]+)(?=</)`
  
     > replace: `{{'$1' | translate }}`
  
  
2. change placeholder

     > find: `(placeholder=")([\w\s]+)(")`
  
     > replace: `$1{{'$2' | translate }}$3`
  
  
________________________
