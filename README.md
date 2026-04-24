# Sample Java Backend

A sample Java backend project used for testing [Transync](https://github.com/kaisarnajar-driod/translation-automation-tool) — the translation automation tool.

## Clone

```bash
git clone git@github.com:kaisarnajar-driod/sample-backend-java.git
```

## String Resources

- **Format:** JSON
- **Path:** `src/main/resources/i18n/en/strings.json`
- **Translated output:** `src/main/resources/i18n/{lang}/strings.json`

## Add to Transync

```bash
transync add sample-backend-java git@github.com:kaisarnajar-driod/sample-backend-java.git \
  --strings-path src/main/resources/i18n/en/strings.json \
  --languages hi,ar,fr,es
```
