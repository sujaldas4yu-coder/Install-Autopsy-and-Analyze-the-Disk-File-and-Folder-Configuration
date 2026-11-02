# Install Autopsy and Analyze the Disk File and Folder Configuration

## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="1920" height="1200" alt="Screenshot 2026-11-02 121933" src="https://github.com/user-attachments/assets/5e1d982b-fe1c-45cd-83cc-111c61df718a" />
<img width="1920" height="1140" alt="Screenshot 2026-11-02 114416" src="https://github.com/user-attachments/assets/c6c1ded2-5729-41a1-a028-149728c8c7fc" />
<img width="1920" height="1200" alt="Screenshot 2026-11-02 114438" src="https://github.com/user-attachments/assets/74f11d64-ae4a-4a7c-bf33-204c9e235202" />
<img width="1920" height="1140" alt="Screenshot 2026-11-02 114457" src="https://github.com/user-attachments/assets/b382cb30-445b-4e18-8409-5839b4db8ac3" />
<img width="1902" height="1130" alt="Screenshot 2026-11-02 121752" src="https://github.com/user-attachments/assets/904e5d74-1692-4d09-9167-a0f480e7a98d" />
<img width="1902" height="1130" alt="Screenshot 2026-11-02 121826" src="https://github.com/user-attachments/assets/1e28cc6a-8bb6-4ac9-b379-1916202f49f5" />
<img width="1902" height="1130" alt="Screenshot 2026-11-02 121841" src="https://github.com/user-attachments/assets/3c3060f8-20c9-4f60-a89e-4642624e7d4f" />
<img width="1902" height="1130" alt="Screenshot 2026-11-02 120246" src="https://github.com/user-attachments/assets/375f9408-1c26-4dd9-94cb-4e0ca2e50f11" />
<img width="1920" height="1140" alt="Screenshot 2026-11-02 121423" src="https://github.com/user-attachments/assets/15df6fcd-f819-40ad-bd9e-ce0ef4d8b6a0" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
