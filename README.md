# Clarkson University: Keystroke Dataset Collection

*Available to researchers under the CITeR Database Release Agreement.*

*To request this dataset, please contact citer@clarkson.edu and indicate the specific dataset.*

This dataset is collected from 39 subject users in two separate laboratory sessions. Each session takes about one hour, and contains about 10K keystrokes.

Thirty four users have completed the two sessions.

There are three users for whom we have data only for one session,  and two users whose data are aborted at the beginning of the second session.

We have also recorded the video for a user’s facial expression and hand movement when they type.

**The data are the result of each subject performing the following tasks in a laboratory:**

1. Password Entries: 3 different passwords, each typed 20 times
2. Free Text Questions10 questions (8 Survey style, 2 Scene Description)500 characters typed for each question
3. Transcription of Steve Jobs’ Commencement Speech split in two pieces.

There is one folder for each subject, named by a subject id. Under each folder, there are two files, one for each session where the subject was invited into the lab to contribute some typing.

For example, under folder 1227981, you will find two files 1227981_V1.txt (session 1) and 1227981_V2.txt (session 2) for subject 1227981. Within each file, there are multiple lines, each corresponding to one typing task the subject performed in the lab session.

The format of each line is explained as follows, using the first line that I took from 1227981_V1.txt as example:

Each line is separated into four fields separated by a tab key.

1227981_01 (id_session) 1 (task)

1ut0eicq3ml85ni3geavqrl6e4 (please ignore)

0(a):61(b):1312903092233(c):1242719(d),

1(a):61(b):1312903092295(c):62(d),0(a):62

(b):1312903092404(c):109(d), … ,

where:

a: 0 means key pressed; 1 means key released.

b: key code. Note that this is a browser key code, not ASCII code.

c: time stamp in millisecond

d: time lapse since last keystroke, which is redundant as it can be calculated from the current time stamp and the last time stamp. e.g., 62 = 1312903092295 -1312903092233

Esra Vural, Jiaju Huang, Daqing Hou, Stephanie Schuckers,Shared Research Dataset to Support Development of KeystrokeAuthentication, International Joint Conference on Biometrics, IJCB 2014. September 29-October 2 2014, Clearwater,Florida, USA.

Information source from the depricated link at: https://citer.clarkson.edu/research-resources/biometric-dataset-collections-2/clarkson-university-keystroke-dataset/.
