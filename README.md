<br />

  <p align="center">
    Make your Interview Meet cool with InterviewMate
  </p>

# About The Project

It is a **Docker-based sandbox environment** for running code snippets. For each piece of provided code, it builds a fresh Docker-based container, executes it, and then returns the results. The major programming languages C, C++, Python, Java, and javascript are supported, and more language support can be added.
It can also be used as a platform for interviews where the interviewer can create a special link or code. By using the specially constructed URL or code, a user may access the interview. The screen will be shared in real time after clicking on a specific link to start the interview. It implies that any modifications made to one screen will be reflected on all users' screens during that specific interview. They can use a video call at any time during the interview.

## Features:

1. **Home Screen**

   The homepage consists of the following elements:
   **_Login with Google_**
   , **_IDE for Coding_**
   , **_Host an Interview_**
   , **_Enter an Interview_**
   , **_Hosted Interviews_**

2. **IDE Screen**:
   1. **_Dual Theme Implementation (Light and Dark Mode)_**
   2. **_Various Languages Support_**: c, c++, python, java, javascript
   3. **_IDE to Code_**
   4. **_Input_**: Input Section for input of the Code if required
   5. **_Output_**: Output Section to Display the Output or to Show Error if occurred

3. **Hosted Interviews Screen**:

   1. **_List of Previously Hosted Interview Codes_**: Contains Timestamps, Share Code , Enter Internview, Delete, Copy Interview Link functionality

4. **Interview Screen**:

   All features are same as that of "IDE Screen" with following additional features.

   1. **_Realtime Code sharing and Editing_**
   2. **_Video-call_**

## Technologies Used

- Docker for Containerisation
- Socket io Realtime
- Node.js and Express Backend
- Mongodb for Database
- Reactjs Frontend
- Redux State Management

## Setup steps

### Clone Repository

```bash
git clone https://github.com/rohitsigar/Interview-Lit.git
```

### Install Server Dependencies

```bash
cd rce-server
npm install
```

### Install Client Dependencies

```bash
cd client
npm install
```

### Build Executor Image

```bash
cd rce-server
cd executor
docker build -t executor:1.0 .
```

### Start Server

```bash
npm run dev
```

### Start Client

```bash
npm start
```
