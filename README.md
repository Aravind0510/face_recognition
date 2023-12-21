# face-recognition-based-attendance-system  

# Problem statement :
 * In a traditional system, a school authority responsible for taking attendance should mark it down manually.

 * Marking each student takes time from school hours, which is better suited for revisions, etc.

 * But to save time, one attendance is taken per day and whole day attendance is not calculated properly.

# solution:
  Our solution uses an object detection model to track the faces of students who have registered in the platform.

  The face tracking is done at real time, in the form of live video.

  The live streaming of video is done by integrating this model with Raspberry Pi microprocessor

  The model is trained to recognize the student faces and record their attendance automatically.

  After finding the students, their presence is marked in excel sheet by itself.
