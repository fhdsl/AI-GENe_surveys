# AI-GENe_surveys

### Rendering surveys

IRB generally requires an editable document. Render the survey as HTML->PDF to ensure questions are printed:

```
# Run in R console
# Create nice html and pdf
# pagedown::chrome_print("survey.qmd", "01_Faculty_Pre_Post_Retrospective.pdf")
```

Create a Word editable version:

```
# Run in Terminal
# Create simple word doc
# pandoc survey.html -o 01_Faculty_Pre_Post_Retrospective.docx
```

Upload docx and pdf to Google Drive when finished.
