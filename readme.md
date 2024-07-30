# public_datasets

> Datasets used within the SeSGx ecossystem.

Each dataset is a `.json` file with the following shape:

```jsonc
{
    // name of the secondary study
    "name": "alli",
    // the studies included in the secondary study's GS.
    "gs": [
        {
            // id of the study, respective to the current secondary study
            "id": 3,
            // metadata
            "title": "Data augmentation using... Omitted for brevity",
            "abstract": "Dysarthria is a speech-motor disorder... Omitted for brevity",
            "keywords": "Microphone array, multi-resolution..., Omitted for brevity",
            // references of this study
            "references": [
                // ID of the referenced study
                38
            ]
        },
    ]
}
```
