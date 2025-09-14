DAY- 1 Jenkins 

Create a Classic Job

From Jenkins Dashboard → click New Item.

Enter a job name (e.g., First-classic-job).

Select Freestyle Project (Classic job).

Click OK.

Configure the Job

In the job configuration page, scroll down to Build Steps.

Select Execute Shell (for Linux/Mac) or Execute Windows batch command (for Windows).

Add the following command:

echo "Hello World"

This is a simple script to test whether Jenkins can run shell commands.

Save and Run

Click Save.

On the job page, click Build Now.

Open Console Output to verify that Hello World is printed.
<img width="1911" height="846" alt="image" src="https://github.com/user-attachments/assets/744deb07-4d8c-4430-a7e6-597284274604" />
<img width="1882" height="527" alt="image" src="https://github.com/user-attachments/assets/8e2d8364-1dcc-44cf-ba61-6438f53929f2" />

