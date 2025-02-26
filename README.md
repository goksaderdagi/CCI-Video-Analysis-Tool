# CCI Video Analysis Tool

## Introduction
CCI Video Analysis Tool is a software application designed to assist users in annotating and analyzing traffic videos. It provides features for marking lanes, vehicles, and various events within the video, as well as managing and exporting the annotated data.

## System Requirements
- **Operating System:** Windows

## Getting Started
1. **Download the Tool:**
   - Click on the green "Code" button located above this repository.
   - Select "Download ZIP" from the dropdown menu.
   - Save the ZIP file to your computer.

2. **Extract the ZIP File:**
   - Navigate to the downloaded ZIP file on your computer.
   - Right-click on the file and select "Extract All...".
   - Choose a destination folder where you want to extract the files.

3. **Locate the Executable:**
   - Once extracted, navigate to the extracted folder.
   - Look for the `dist` folder.
   - Inside the `dist` folder, you will find the `CCIVideoAnalysisTool.exe` file.

4. **Run the Tool:**
   - Double-click on `CCIVideoAnalysisTool.exe` to launch the CCI Video Analysis Tool.

5. **Getting Started:**
   - Follow the instructions in the tool's interface to load videos, annotate data, and export results.

## Interface Overview

### Main Window
- **Canvas for Video Playback and Annotation:** Displays the video feed for drawing traffic lanes and markings.
- **Data Entry Table:** Allows entry of vehicle and event data.
- **Playback Controls:** Buttons for video playback.
- **Main Control Settings:** Options for loading video, drawing lanes and markings, managing annotations, and exporting data.

### Playback Window
- **Canvas for Video Playback and Annotation:** Displays annotated video with traffic lanes and markings.

### Main Control Settings
- **Load Video:** Load a video file for annotation.
- **Draw Traffic Lanes:** Activate mode to mark traffic lanes.
- **Draw Markings:** Activate mode to mark specific points or lines.
- **Save Lines:** Save marked lines configuration.
- **Load Lines:** Load previously saved lines configuration.
- **Undo:** Undo the last annotation action.
- **Add Row:** Add a new row to the data table.
- **Export Data:** Export annotated data to CSV.
- **Cancel:** Cancel current annotation.
- **Help:** Access user manual.

### Playback Controls
- **Play:** Start video playback.
- **Pause/Resume:** Pause or resume playback.
- **+1h:** Skip forward by 1 hour.
- **-1h:** Skip backward by 1 hour.
- **+1s:** Skip forward by 1 second.
- **-1s:** Skip backward by 1 second.
- **Frame Forward/Backward:** Move frame by frame.
- **Right Side Line Entry:** Adjust right side line numbers.
- **Time Label:** Display video timestamp.

## Data Entry Table Columns and Usage
- **VehID:** Vehicle identifier.
- **Vehicle Type:** Type of vehicle (Car, Bus, Light-duty Truck, Truck).
- **Entry Lane:** Initial lane position.
- **Exit Lane:** Lane exited.
- **Type of Leading Vehicle:** Leading vehicle type (None, Car, Bus, Light-duty Truck, Truck).
- **Brake:** Timestamp for brakes applied.
- **Onset of Yellow:** Timestamp for yellow light onset.
- **Onset of All-red:** Timestamp for all-red light onset.
- **Decision:** Driver's decision (Stop, Go).
- **Observed Traffic Conflict:** Recorded traffic conflicts (optional).
- **Movement:** Vehicle direction (Thru, Left, Right).
- **Additional Comments:** Additional notes.

## ML-MM-MR (Left-Middle-Right View) Columns
- **ML Columns:** Timestamps for vehicles passing marking lines on the left side.
- **MM Columns:** Timestamps for vehicles passing marking lines in the middle.
- **MR Columns:** Timestamps for vehicles passing marking lines on the right side.

## Exporting Data
1. **Click "Export Data" Button**
   - Choose save location and filename.
   - Click "Save" to export CSV file.

## Step-by-Step Guide
1. **Load the Video**
   - Click "Load Video" and select video file.
   - Record video name in entry box.

2. **Draw Markings**
   - Click "Draw Markings" and draw lines.
   - Adjust right side lines if needed.

3. **Highlight Lane Lines (Optional)**
   - Click "Draw Traffic Lanes" and draw lanes.
   - Click "Done with Lanes" to finalize.

4. **Save and Load Lines**
   - Use "Save Lines" to save current lane configurations.
   - Use "Load Lines" to load previously saved configurations.

5. **Playback Controls**
   - Use controls to navigate video frames.

6. **Record Vehicle Characteristics**
   - Use Data Entry Table to record vehicle details and events.
   - Click "Add Row" to add new entries.
   - Record timestamps by clicking appropriate fields.

7. **Export Data**
   - Click "Export Data" to save annotated data.
