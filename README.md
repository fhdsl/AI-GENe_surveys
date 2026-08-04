# AI-GENe_surveys

### Rendering surveys

IRB generally requires an editable document. Render the survey as HTML->PDF to ensure questions are printed:

```
pagedown::chrome_print("survey.qmd")
```

Then, open the pdf in Microsoft Word, allowing it do do any necessary conversion. Upload this docx to Google Drive.
