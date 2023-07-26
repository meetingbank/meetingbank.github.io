---
layout: about
title: Home
permalink: /
subtitle:

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

## Overview

MeetingBank, a benchmark dataset created from the city councils of 6 major U.S. cities to supplement existing datasets. It contains 1,366 meetings with over 3,579 hours of video, as well as transcripts, PDF documents of meeting minutes, agenda, and other metadata. On average, a council meeting is 2.6 hours long and its transcript contains over 28k tokens, making it a valuable testbed for meeting summarizers and for extracting structure from meeting videos. The datasets contains 6,892 segment-level summarization instances for training and evaluating of performance. 

## Acknowledgement

Please cite the following paper in work that makes use of this dataset:

[MeetingBank: A Benchmark Dataset for Meeting Summarization](https://arxiv.org/abs/2305.17529)\
Yebowen Hu, Tim Ganter, Hanieh Deilamsalehy, Franck Dernoncourt, Hassan Foroosh, Fei Liu\
In main conference of Association for Computational Linguistics (ACL'23), Toronto, Canada.


## Bibtex
```
@inproceedings{hu-etal-2023-meetingbank,
    title = "MeetingBank: A Benchmark Dataset for Meeting Summarization",
    author = "Yebowen Hu and Tim Ganter and Hanieh Deilamsalehy and Franck Dernoncourt and Hassan Foroosh and Fei Liu",
    booktitle = "Proceedings of the 61st Annual Meeting of the Association for Computational Linguistics (ACL)",
    month = July,
    year = "2023",
    address = "Toronto, Canada",
    publisher = "Association for Computational Linguistics",
}
```

## Resources

MeetingBank dataset will be hosted at Zenodo. The audio files of each meeting will be hosted individually on Huggingface. All resources will includes meeting audio, transcripts, meetingbank main JSON file, summaries from 6 systems and human annotations.

**Summary, Segments Transcripts and VideoList**: [zenodo](https://zenodo.org/record/7989108)

**Meeting Videos**: All meeting videos can be found in https://archive.org/

[Alameda](https://archive.org/details/meetingbank-alameda), [Boston](https://archive.org/details/meetingbank-boston), [Denver](https://archive.org/details/meetingbank-denver), [Long Beach](https://archive.org/details/meetingbank-long-beach) ,[King County](https://archive.org/details/meetingbank-king-county), [Seattle](https://archive.org/details/meetingbank-seattle)


**Meeting Audios**: [HuggingFace Dataset](https://huggingface.co/datasets/huuuyeah/MeetingBank_Audio)

Some scripts can be found in github repo [MeetingBank_Utils](https://github.com/YebowenHu/MeetingBank-utils)
