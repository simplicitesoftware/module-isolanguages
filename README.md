<!--
 ___ _            _ _    _ _    __
/ __(_)_ __  _ __| (_)__(_) |_ /_/
\__ \ | '  \| '_ \ | / _| |  _/ -_)
|___/_|_|_|_| .__/_|_\__|_|\__\___|
            |_| 
-->
![](https://docs.simplicite.io//logos/logo250.png)
* * *

`ISOLanguages` module definition
================================



`ISOLanguage` business object definition
----------------------------------------

ISO 639 languages

### Fields

| Name                                                         | Type                                     | Required | Updatable | Personal | Description                                                                      |
|--------------------------------------------------------------|------------------------------------------|----------|-----------|----------|----------------------------------------------------------------------------------|
| `isoLngName`                                                 | char(100)                                | yes      | yes       |          | ISO language name                                                                |
| `isoLngCode`                                                 | char(2)                                  | yes*     | yes       |          | 2 digits code (ISO-639-1)                                                        |
| `isoLngCode3Digits`                                          | char(3)                                  | yes      | yes       |          | 3 digits code (ISO-639-3)                                                        |
| `isoLngCode3DigitsT`                                         | char(3)                                  | yes      | yes       |          | 3 digits code (ISO 639-2/T)                                                      |
| `isoLngCode3DigitsB`                                         | char(3)                                  | yes      | yes       |          | 3 digits code (ISO-639-2/B)                                                      |

