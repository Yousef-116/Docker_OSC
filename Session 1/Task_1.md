# Task one

## Q1. 4 images
- busybox
- alpine 
- erseco/alpine-php-webserver
- ahmedyasser9/osc-server
```
docker images
```

## Q2. Create a container from alpine and has it print out what is inside /etc/hostname file

```
docker run alpine cat /etc/hostname

```
## Q3. Download ubuntu image with the noble tag

```
docker pull ubuntu:noble
```
## Q4.  Run a container using erseco/alpine-php-webserver image and detach it

```
docker run -p 8080 erseco/alpine-php-webserver

```
>image
![step four image](step_4.1.png)
![step four image](step_4.2.png)

## 5. go back

```
cd ..

```
## 6. Create a Unique Dirctory

```
mkdir "-"

cd Documents/-/

```
>image
![step four image](step_6.1.png)
![step four image](step_6.2.png)

## 7. Copy Directory

```
cp -r Documents My_Documnts
ls

cd My_Documents
ls

```
>image
![step four image](step_7.png)

## 8. show Hidden Files

```
ls -a 

```
>image
![step four image](step_8.png)

## 9. Move files

```
mv file2.txt ~/Yousef\ Mostafa/
ls

mv file3.txt ~/Yousef\ Mostafa/
ls

cd..
ls
```
>image
![step four image](step_9.png)

## 10. Remove your Directory

```
ls

rm -r "Yousef Mostafa"
ls

```
>image
![step four image](step_10.png)

