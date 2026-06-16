Hands-On Practice Lab 1

Create a directory structure:

mkdir -p devops/linux/practice

Navigate into it:

cd devops/linux/practice

Create files:

touch app.log
touch nginx.conf
touch docker.txt

List files:

ls -la

Add content:

echo "Linux Practice" > docker.txt

View content:

cat docker.txt

Change permission:

chmod 755 docker.txt

Check permission:

ls -l

Search file:

find . -name "*.txt"
Recommended Order for Linux Fundamentals
Linux File System
Navigation Commands
File Operations
Permissions
Users & Groups
Process Management
Package Management
Networking Basics
Logs & Troubleshooting
Practice Labs
Your first task

Open a Linux machine (Ubuntu VM, WSL, EC2, or a Linux server) and practice these commands until you can use them without looking at notes:

pwd
ls
cd
mkdir
touch
cp
mv
rm
cat
find
grep
chmod
chown
ps
top
ip addr

Once you've completed that, we can move to Lesson 1: Linux File System Deep Dive with exercises and DevOps-focused real-world examples.