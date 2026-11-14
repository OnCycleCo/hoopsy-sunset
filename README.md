# Hoopsy sunset

This repository is where a Hoopsy shutdown notice would be published, if Hoopsy ever closes.

Hoopsy (https://hoopsy.app) 0.5.1 and later look for `sunset.txt` here, on hoopsy.app, and on
the license server, but only when a copy can't be used (its license can't be checked). A notice
is signed with Hoopsy's offline sunset key. Every copy that sees one turns its license check off
for good, so it keeps working without any of Hoopsy's servers.

There is no `sunset.txt` here, which means Hoopsy is running normally.
