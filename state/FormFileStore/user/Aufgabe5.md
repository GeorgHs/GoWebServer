# Request/Response

Basiert auf synchroner Kommunikation, d.h. auf einen Request(Anfrage) gibt es eine Response. Ohne Request gibt es keine Response(Antwort). Eine Reponse gehört immer zu einer Reponse.

Request/Response ist das klassische HTTP(bis 2.0, ab da wurde das Konzept aufgeweicht) und wird somit für SOAP und natürlich REST und Messaging verwendet.

# Datagram

Basiert auf asynchroner Kommunikation. Wird deshalb häufig benutzt für Anwendungen die keinen(bzw. nicht immer einen) Bedarf nach Antwortnachrichten haben.
Dieses "Kommunikationsschema" ist somit z.b. beim wiederholten Abfragen von Informationen.