# flutter_job_portal

مرحبا يا جماعة كيفكن .. هدا النسخة الأساسية من المشروع </br>
انتو بيبقى عليكن انو تعملو الخطوات التالية:</br>
1- بدكن تعملو fork للكود الأساسي هاد فبيصير عندكن نسخة منو على ال github. 
</br>2- بتروحو على ال fork تبعكن و بتنسخو الرابط تبعو</br>
3- بتروحو على مكان ما بدكن تنشئوا المشروع بعدين على التيرمينال تبعكن او تيرمينال اندرويد ستديو او تيرمينل الفيجوال و بتكتبو:</br>
```
//هون بتكتبو الرابط بدون الأقواس هاي
git clone <forked_repo_url> 
```
</br>4- بتعملو تعديلات على الكود تبعكن و على الملفات و بعدين بترجعو مكان ما انشئتو المشروع او عملتو استنساخ للكود من github بعدين بتروحو للتيرمينال و بتكتبو:
```
git add .
git commit -m "commit"
```
5- بس خلصتو تعديل و اتأكدتو منو بتكتبو بالتيرمينال
```git push origin master```
و طبعا ال origin بتدل على الرابط اللي عملتو منو استنساخ للكود و master بتدل على اسم الفرع ، الخطوتين 4 و 5 بتعمليوهن كل مرة بتعدلو على الكود مشان ترفعو التعديل على النسخة الخاصة منكن من الكود بال github 
</br>6- بتروحو على github على ال fork تبعكن و بتعملو pull request : </br>
New Pull Request -> Create Pull Request</br>
7-اذا في ملفات جوات المشروع ما بدكن ترفعوها على ال github بتعملو ملف جوات ال directory تبع المشروع و بتسمو الملف </br>
.gitignore</br>
متل ما هوي ، يعني لا هوي لاحقة و لا اي شي بس بتكتبو اسمو هيك و جواتو فيكن تكتبو الملفات او المجلدات اللي ما بتنرفع لما بتعملو الخطوتين 4 و 5 و هاد مثال بتكتبو فيه بهالطريقة :</br>
../project_directory/.gitignore (جوات الملف)
```
#Simply write the name of directory or file
build/
.dart_tool/
pubspec.lock

*.log        # Ignore all files with the .log extension
*.pdf        # Ignore all PDF files
/build/      # Ignore the build directory in the root of the repository
**/build/    # Ignore the build directory in any subdirectory

# Ignore build artifacts
build/

# Ignore log files
*.log

file\ with\ space.txt

# Ignore all files in the build directory
build/

# But don't ignore this specific file in the build directory
!build/special-file.txt
```...............................................................................................................
