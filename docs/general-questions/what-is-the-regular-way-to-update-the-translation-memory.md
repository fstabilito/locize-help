# What is the regular way to update the translation memory?

The namespace files are the consumable translation memory. So keeping your namespaces uptodate automatically keeps your TM clean and uptodate. Doing a TM lookup for a segment shows all possible (fuzzy) matches including a link to the source segment.

Every namespace / project acts directly as the TM. That way maintaining it and keeping it consistent is very natural and not an extra work. You can import tmx to a namespace.