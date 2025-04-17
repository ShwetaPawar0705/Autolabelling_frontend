# Video Processing App Documentation

A React + TypeScript frontend application for uploading and annotating videos with object detection and segmentation via websocket.

## Tech Stack

1. React
2. TypeScript
3. WebSocket for real-time updates

## Installation

```bash
npm install
```
This creates:
- `node-modules` folder
- `package-lock.json` file

## Running the Application

```bash
npm run dev
```

## Folder Structure

```
src/
├── components/
│   ├── Header.tsx            # Application header component
│   ├── Parallax.tsx          # Parallax effect component
│   ├── VideoProcessor.tsx    # Handles video processing logic
│   ├── Videostatus.tsx       # Displays video processing status
│   └── Videouploader.tsx     # Handles video upload functionality
├── api/
│   ├── api.ts                # API service functions
├── App.tsx               
├── index.tsx            
```
