# casa
Ejercicios varios
# THIS IS ONLY FOR THE gitattributes REPOSITORY.
# Handle line endings automatically for files detected as text
# and leave all files detected as binary untouched.
*               text=auto

#
# The above will handle all files NOT found below
#
# These files are text and should be normalized (Convert crlf => lf)
*.gitattributes text
.gitignore      text
*.md            text

#
# Exclude files from exporting
#

.gitattributes  export-ignore
.gitignore      export-ignore

#
# Enable syntax highlighting for files with `.gitattributes` extensions.
#
*.gitattributes linguist-language=gitattributes
