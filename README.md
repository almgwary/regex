# Regex
Collection of useful regex

# Ngx Translate
ngx-translate Auto inject translate pipe in the html tags and placeholders
1. change tag

     > find: `(?<=>)([\w\s]+)(?=</)`
  
     > replace: `{{'$1' | translate }}`
  
  
2. change placeholder

     > find: `(placeholder=")([\w\s]+)(")`
  
     > replace: `$1{{'$2' | translate }}$3`
  
  
________________________

# Email

     ^[a-z0-9._%+-]+@[a-z0-9.-]+\.[a-z]{2,4}$

# Password

Password must be at least 9 characters long, contain letters and numbers, special characters

      /^(?=.*[A-Z])(?=.*[!@#\$%\^&\*])(?=.{9,})/
