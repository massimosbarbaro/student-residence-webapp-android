# WebAppDijaski: Android app for the staff timetables and messages of a student residence

*App Android per gli orari del personale e i messaggi di un convitto per studenti*

**MIT App Inventor (Android)** · 2020 · version 1.0  
Author: **Massimo Sbarbaro** ([ORCID 0009-0006-8965-9013](https://orcid.org/0009-0006-8965-9013))

## Overview

WebAppDijaski is a small Android client for the website of a student residence. It gives the staff one-tap access to the published timetables of the kitchen, the night service and the educators and to the internal message board, each in its own screen, and handles the WordPress login page and the back navigation inside an embedded web viewer. Slovene interface.

I designed and programmed this application in 2020. It is published here in 2026 as part of the documented record of my software work, with a permanent DOI on Zenodo.

## Main functions

- Home screen with buttons for the kitchen, night-service and educators' timetables and for the messages page (`Screen1`).
- One screen per timetable (`Kuh`, `NOCNA`, `Vzg`) and one for the message board (`SPOROCILA`), each with an embedded web viewer.
- Detection of the login page and of external links, with back and home navigation between screens.

## Data

No local data: pages are loaded from the residence website (domain replaced by `example.org` in this publication).

## Technology

MIT App Inventor 2: WebViewer, Buttons, arrangements; permissions INTERNET and network state.

## Repository contents

| Path | Content |
|---|---|
| `project/*.aia` | The App Inventor project, ready to be imported (*Projects → Import project (.aia)* at ai2.appinventor.mit.edu). |
| `source/src/` | Screen designs (`.scm`, JSON) and block programs (`.bky`, Blockly XML), one pair per screen. |
| `source/assets/` | Button icons and App Inventor extensions used by the project. |
| `source/youngandroidproject/` | Project properties (package, version, theme). |

## What is not included

Photographs, illustrations, logos, sound recordings and stock images are **not** included: most of them belong to third parties (photographers, illustrators, performers, the commissioning organisation). The project still opens in App Inventor; the components that showed those media are simply empty. The name of the commissioning organisation and the funding statement have been removed, together with addresses, telephone numbers, e-mail addresses and websites of third parties; web addresses used by the app have been replaced with `example.org`. The compiled APK and its signing key are not published.

## How to cite

Use the citation metadata in [`CITATION.cff`](CITATION.cff) (GitHub: *Cite this repository*). Each release is archived on Zenodo with its own DOI.

> Sbarbaro, Massimo. *WebAppDijaski: Android app for the staff timetables and messages of a student residence (MIT App Inventor (Android), 2020)*. Software, version 1.0. GitHub: https://github.com/massimosbarbaro/student-residence-webapp-appinventor

## License

Released under the [MIT License](LICENSE). © 2020 Massimo Sbarbaro.
