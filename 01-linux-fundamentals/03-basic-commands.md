Current Directory
pwd

Output:

/home/devops

List Files
ls

Detailed:

ls -l

Hidden files:

ls -la

Change Directory
cd /etc

Go home:

cd ~

Go back:

cd ..

------------------------------------------------------------------

Create File
touch file.txt

Create Directory
mkdir project

Nested:

mkdir -p devops/docker/nginx

Copy

cp file.txt backup.txt

Directory:

cp -r source target

Move / Rename

mv file.txt newfile.txt
-------------------------------------
Delete

File:

rm file.txt

Directory:

rm -rf project

⚠️ Be careful with:

rm -rf /

Module 5: Viewing File Content

Display File
cat file.txt

First Lines
head file.txt

Last Lines
tail file.txt

Live log monitoring:

tail -f app.log

Very important for DevOps.

Module 6: Search Operations
Find Files
find /home -name "*.txt"

Search Inside Files
grep "error" app.log

Case insensitive:

grep -i error app.log