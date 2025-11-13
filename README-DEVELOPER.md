
This is the repository where Inkberry fetches the remote Inchiostro template files from.


The "template-package.json" file is fetched from here:

https://github.com/Daniel-Wittgenstein/inchiostro-dist/blob/main/template-package.json

This is used to display info about Inchiostro in the select template dialog.

Make sure the version in this file corresponds to the version of the zip file.



The template zip file is fetched from here:

https://github.com/Daniel-Wittgenstein/inchiostro-dist/blob/main/inchiostro-latest.zip

It should include all files the template needs to run.

It should NOT include an "ink-package.json" file (Inkberry creates that one.)

This is downloaded and unzipped when the user creates a new Inchiostro project.



All other files here have no special meaning.


Creating a new version:

Zip up the entire contents of the inchiostro-dev repo manually and add it here, replacing inchiostro-latest. Then change template-package.json.



