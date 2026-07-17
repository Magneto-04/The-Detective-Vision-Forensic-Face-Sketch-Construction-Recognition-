# The Detective Vision: Forensic Face Sketch Construction & Recognition

A desktop application built for law enforcement that lets users construct composite face sketches from eyewitness descriptions (using a drag-and-drop interface) and automatically match them against a criminal facial database using deep learning.

## What it does
- **Face sketch construction:** Users build a composite face sketch by selecting and positioning predefined facial features (head, eyes, nose, lips, ears, etc.) via a drag-and-drop canvas — no artistic training needed.
- **Backward compatibility:** Also accepts previously hand-drawn sketches from forensic artists, so the platform works alongside traditional methods, not just instead of them.
- **Face recognition/matching:** Matches the constructed (or uploaded) sketch against a criminal facial database using deep learning, returning matched records with a confidence/accuracy score.

## Tech stack
- **Language/Framework:** Java, JavaFX (desktop UI)
- **Cloud:** AWS (storage and processing for recognition workload)
- **Database:** SQLite
- **Authentication:** User authentication(Username & Password), custom machine-locking (HD ID + MAC address binding)
- **IDE:** IntelliJ IDEA / NetBeans / Eclipse


## How to run
```bash
# Clone the repo (once pushed)
git clone https://github.com/Magneto-04/[repo-name].git

# Open in IntelliJ IDEA / NetBeans / Eclipse (JavaFX project)

# Configure AWS credentials for cloud storage/processing
# [Add: which AWS services are used — S3, EC2, etc., and how credentials are configured]

# Run the main JavaFX application
```

## Publications
This project was published as:
- **Research paper** — IJSREM (International Journal of Scientific Research in Engineering and Management), November 2025. 
- **Implementation paper** — IJSREM, June 2026. 

