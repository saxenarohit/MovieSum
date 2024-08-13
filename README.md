# MovieSum: An Abstractive Summarization Dataset for Movie Screenplays
Paper link: [ACL'24](https://aclanthology.org/2024.findings-acl.239/)

The dataset can be downloaded from the Hugging Face hub:

[rohitsaxena/MovieSum](https://huggingface.co/datasets/rohitsaxena/MovieSum)

## Dataset Summary

MovieSum consists of 2,200 movie screenplays and their corresponding Wikipedia summaries. It is a long-form summarization task where the mean length of movie screenplays is approximately 34K. We manually formatted the movie screenplays to represent their structural elements. We also provide the IMDB ID for each movie to facilitate the collection of additional metadata.

## Dataset Statistics
|                 |     |
|----------------------------|-----------------|
| **Total Movie Screenplays**    | 2,200           |
| **Mean Screenplay Length**     | 34,275          |
| **Mean Summary Length**        | 793             |

Each movie screenplay is in XML format with the following DOM structure:

```
<script>
<scene>
<stage_direction>..</stage_direction>
<scene_description>...</scene_description>
<character>..</character>
<dialogue>..</dialogue>
...
</scene>
<scene>
...
</scene>
<script>

```

## Dataset Structure

The dataset is divided into three parts:
- **Training Set**: 1800 movie screenplays, summaries, and IMDB ids.
- **Validation Set**: 200 movie screenplays, summaries, and IMDB ids.
- **Test Set**: 200 movie screenplays, summaries, and IMDB ids.

## License
Creative Commons Attribution Non Commercial 4.0

## Citation
```
@inproceedings{saxena-keller-2024-moviesum,
    title = "{M}ovie{S}um: An Abstractive Summarization Dataset for Movie Screenplays",
    author = "Saxena, Rohit  and
      Keller, Frank",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Findings of the Association for Computational Linguistics ACL 2024",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand and virtual meeting",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.findings-acl.239",
    pages = "4043--4050"
    }
```

## Baseline Code
Will be uploaded soon!

