# VideoEvent_Dataset

A collection of video event annotations and external video links for event recognition research.

---

## 📂 Repository Structure

- `videos/video_list.csv` : List of videos with download links.
- `annotations/event_annotations.csv` : Event annotations with timestamps and descriptions.
- `thumbnails/` (optional) : Sample thumbnails or frames.
- `README.md` : Dataset documentation.

---

## 🎥 Video Data

Videos are stored externally on Google Drive and can be accessed via the links in `videos/video_list.csv`.

Example:

| Video ID  | Link                                                                |
|-----------|---------------------------------------------------------------------|
| V001      | [Download](https://drive.google.com/file/d/xxxx/view?usp=sharing)   |
| V002      | [Download](https://drive.google.com/file/d/yyyy/view?usp=sharing)   |

---

## 🗂 Event Annotations

| Event                   | Video ID  | Start Time | End Time | Duration (sec) |
|-------------------------|-----------|------------|----------|----------------|
| Robots traffic           | V001      | 03:37      | 04:15    | 38             |
| People lift, snatch bag  | V001      | 04:26      | 05:07    | 41             |

See full annotations in `annotations/event_annotations.csv`.

---

## 📑 License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

---

## 🤝 Citation

If you use this dataset, please cite:
> Your Paper Title (Year), Authors, DOI/URL

---
