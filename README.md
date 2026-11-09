# Satu-Langkah

# Satu Langkah

Satu Langkah is a calm, teacher-led vocabulary practice prototype for autistic pupils. It helps a pupil work through one short, visual learning mission at a time: take or choose a photo of an object, hear a teacher-approved word, and complete a simple matching activity. The pupil can ask for help, repeat the word, take a break, or stop at any point.

## Who it is for

- **Primary learners:** autistic pupils in the initial Standard 1–3 trial group who benefit from clear visual steps, repetition, and predictable choices.
- **Teachers:** educators who prepare short vocabulary activities and want a simple view of what the pupil practised and which supports they used.
- **Future scope:** adapting activities for Standards 4–6 is planned; it is not represented as a completed feature in this prototype.

## How it works

### Teacher setup

1. Open the teacher portal.
2. Set the activity title, subject, standard, learning goal, and pupil code.
3. Choose three to eight words from the teacher-approved word list.
4. Optionally add photos from the device to personalize the activity.
5. Start the mission for the pupil.

### Pupil activity

1. The pupil sees a visual **Now / Next / Done** sequence and starts the mission.
2. They choose a sample object image, take a photo with the device camera, or select an image from the device.
3. The prototype displays a simulated suggested word. The pupil can hear it, confirm it, say they are unsure, or choose from the teacher-approved options.
4. The pupil completes a short word-and-picture matching activity, with optional audio and hints.
5. The pupil sees a calm completion screen or chooses to stop. **Repeat**, **Help**, **Break**, and **Stop** remain available during the activity.

### Teacher review

The teacher can review a neutral session summary showing the learning goal, words attempted, whether a word was confirmed or selected from the list, activity completion, supports used, and optional teacher notes. The summary can be downloaded as a text file.

## Features in this prototype

- Separate pupil and teacher portals.
- English and Bahasa Melayu interface toggle.
- Teacher-selected vocabulary and learning goal.
- Sample object illustrations, camera capture, and image upload.
- Optional spoken word playback and hints.
- Persistent repeat, help, break, and stop controls.
- Adjustable text size, colour theme, sound, and reduced-motion settings.
- Session summary with a text-file download.
- Responsive layout, keyboard focus indicators, accessible labels, and reduced-motion support.

## Try the prototype

Open `satu-langkah-prototype.html` in a modern browser. Sample images and the simulated matching flow can be explored without an account. Camera access depends on browser permissions and generally requires a secure context such as HTTPS or localhost. If camera access is unavailable, use a sample image or upload a picture instead.

## Important prototype limits

- **Photo matching is simulated.** This prototype does not use AI or identify objects from a camera image. The suggested match is demonstration behavior; the pupil can use teacher-approved choices.
- The sample object pictures are illustrations for the demo, not a ready-made curriculum image library.
- This is a learning-support concept, not a diagnostic or therapy tool. It has not been clinically validated or evaluated for learning outcomes.
- It demonstrates a short vocabulary activity, not complete coverage of the Malaysian curriculum.

## Privacy and data

The prototype runs in the browser and has no connected server or cloud account. Some settings and teacher-added images are stored in the browser's local storage, and activity state is held in the current browser session. Treat this as demo behavior, not a production privacy guarantee. Before any real classroom deployment, define consent, retention, access controls, and deletion procedures, and review how images are handled—especially if a future version adds a remote image-recognition service.

## Possible next steps

- Test the activity with teachers, autistic pupils, and families, and revise it from their feedback.
- Replace demo words and pictures with teacher-reviewed curriculum content.
- Offer printable activity cards and an offline-friendly classroom mode.
- Add teacher-controlled lesson templates and carefully scoped progress summaries.
- Explore Standards 4–6 content after validating the initial Standard 1–3 use case.
- If connecting to DELIMa or another government platform, first confirm technical requirements, approvals, privacy rules, and accessibility needs.

