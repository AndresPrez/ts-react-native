This directory ("src") contains all the main code for the typescript ReactNative application.
It is organized into the following directories, each one with its own README.txt file explaining its scope:

Also, "Path Aliases" is implemented in the project (defined in the "tsconfig.json" and "babel.config.js" files)
which allows importing from files without worrying about its relative location.

Please do not implement an index.tsx file within any of these directories.
Make any imports explicit to the file exporting the object needed (ex: 'import Section from "@components/Section"' and not 'import Section from "@components"').
This is a good practice and avoids commiting circular dependencies.

- api (path alias -> "@api")
- assets (path alias -> "@assets")
- components (path alias -> "@components")
- hooks (path alias -> "@hooks")
- navigation (path alias -> "@navigation")
- screens (path alias -> "@screens")


NOTE: Please follow this organizational logic in case additional directories are needed.



