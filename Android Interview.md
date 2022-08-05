## Q1. How to move services to foreground in android?

A - Services always work in Foreground only

B - No,We can't do this query

C - Using startService(Intent intent)

**D - startFordgroud(int id, Notification notification).**

Answer : D
Explanation
We have to call startFordgroud(int id,Notification notification) to make services as foreground services. When it comes to foreground, it will show a notification

---

## Q2. Which permissions are required to get a location in android?

**A - ACCESS_FINE and ACCESS_COARSE**

B - GPRS permission

C - Internet permission

D - WIFI permission.

Answer : A
Explanation
To get a location of a phone, ACCESS_FINE and ACCESS_COARSE permission in manifest file are required. Without these permissions, we can't get the location of a mobile.

---

## Q3 - Is it possible activity without UI in android?

A - No, it's not possible

**B - Yes,it's possible**

C - We can't say

D - None of the above

Answer : B
Without UI, we can call an activity, It will do some background functionalities.

---

## Q4 - How many levels of securities are there in android?

**A - App level security and kernel level security**

B - Android level security

C - Java level security

D - None of the above

Answer : A
Android is having two levels of securities, they are as App level security and kernel level security

---

## Q5 -What are return types of startActivityForResult() in android?

A - RESULT_OK

B - RESULT_CANCEL

C - RESULT_CRASH

**D - A & B**

E - B & C

Answer : D
strartActivityforResult() returns RESULT_OK and RESULT_CANCEL.

---

## Q6 - How many ports are allocated for new emulator?

**A - 2**

B - 0

C - 10

D - None of the above.

Answer : A
Every emulator or device is allocated by 2 ports based on port availability.

---

## Q7 - What is the purpose of super.onCreate() in android?

A - To create an activity

**B - To create a graphical window for subclass**

C - It allows the developers to write the program

D - None of the above

Answer : B
The super.onCreate() will create the graphical window for subclasses and place at onCreate() method.

---

## Q8 - What are commands needed to create APK in android?

A - No need to write any commands

B - Create apk_android in command line

**C - Javac,dxtool, aapt tool, jarsigner tool, and zipalign**

D - None of the above

Answer : C
Using with Javac, we can compile Java files

Use dx tool to convert all Java class files to single dex file

Use AAPT tool to create apk file

Sign the apk file by using jar signer

Zipalign of signed apk

---

## Q9 - How to upgrade SQlite the database from a lower version to higher version in android SQlite?

**A - Using helper Class**

B - Using cursor

C - Using intent

D - None of the above

Answer : A
Explanation
In helper class, we can pass the version numbers in incremental order.

---

## Q10 - What is an anonymous class in android?

A - Interface class

**B - A class that does not have a name but have functionalities in it**

C - Java class

D - Manifest file

Answer : B
Explanation
Anonymous class doesn't have class name but has some functionalities in it.

---

## Q11 - What is transient data in android?

A - Permanent data

B - Secure data

C - Temporary data

**D - Logical data** // like thread code

Answer : D
Transient data is logical data and we can store application logic in it.

---

## Q11 - What does httpclient.execute() returns in android?

A - Http entity

**B - Http response** 

C - Http result

D - None of the above.

Answer : B
Httpclient.execute() executes only once and it will return http response from the server or device, Http entity is embedded the body of the Http response.

Ref: https://www.tutorialspoint.com/android/android_questions_answers.htm
