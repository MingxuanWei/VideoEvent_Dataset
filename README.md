# VideoEvent_Dataset

A collection of video event annotations and corresponding video links for event recognition research.

---

## 📂 Repository Structure

- `video/video_list.csv` : Contains the list of videos and their corresponding download links.
- `annotations/event_annotations.csv` : Contains detailed event annotations with video ID, time range, and duration.
- `README.md` : This documentation file.

---

## 🎥 Video List

All videos are stored externally on Google Drive.  
You can access the full list and links in [`video/video_list.csv`](video/video_list.csv).

Example:

| Video ID | Link                                                             |
|----------|------------------------------------------------------------------|
| V001     | [Link](https://drive.google.com/file/d/1ttJ0jipjbrgNj7kbf_fsQqPDUzYt-AR/view?usp=sharing) |
| V002     | [Link](https://drive.google.com/file/d/1A3TTkXSnK7xDtSwbMgbLmT1n1Qb9vrx5/view?usp=sharing) |

---

## 🗂 Event Annotations

All events are labeled with:
- Event description.
- Time range within the video (`Start Time` - `End Time`).
- Duration in seconds.
- Linked `Video ID` referring to `video_list.csv`.

See detailed annotations in [`annotations/event_annotations.csv`](annotations/event_annotations.csv).

Example:

| Event                    | Video ID | Start Time | End Time | Duration (sec) |
|--------------------------|----------|------------|----------|----------------|
| Robots traffic            | V001     | 03:37      | 04:15    | 38             |
| Phone snatching           | V002     | 00:33      | 00:59    | 26             |

---


