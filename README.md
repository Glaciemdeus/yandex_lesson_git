##### ������!
#### ��� ��������� �� ������������� GIT


**���������** 
1) *pwd* (�� ����. print working directory, ��������� ������� �����) � ������, � ����� � �����; 


2) *ls* (�� ����. list directory contents, ����������� ���������� ����������) � ������ ����� � ����� � ������� �����; 


3) *ls -a* � ������ ����� ������� ����� � �����, �������� ������� ���������� � ������� .; 

4) *cd first-project* (�� ����. change directory, �������� �����������) � ������� � ����� first-project; 


5) *cd first-project/html* � ������� � ����� html, ������� ��������� � ����� first-project; 


6) *cd ..* � ������� �� ������� ����, � ������������ �����; 


7) cd ~  � ������� � �������� ���������� (/Users/Username); 


8) *cd /* � ������� � �������� ����������


**������ � ������� � �������**


*��������* 


1) *touch index.html* (����. touch, �����������) � ������ ���� index.html � ������� �����; 


2) *touch index.html style.css script.js* � ���� ����� ������� ����� ��������� ������, ����� ���������� �� ����� � ���� ������ ����� ������; 


3) *mkdir second-project* (�� ����. make directory, �������� �����������) � ������ ����� � ������ second-project � ������� �����. 
����������� � ����������� 


4) *cp file.txt ~/my-dir* (�� ����. copy, ������������) � �������� ���� � ������ �����; ? mv file.txt ~/my-dir (�� ����. move, �������������) � ��������� ���� ��� ����� � ������ �����. 


**������**

 
1) *cat file.txt* (�� ����. concatenate and print, ����������� � ������������) � ���������� ���������� ���������� ����� file.txt. 
�������� 


2) *rm about.html* (�� ����. remove, ���������) � ����� ���� about.html; 


3) *rmdir images* (�� ����. remove directory, �������� �����������) � ����� ����� images; 


4) *rm -r second-project* (�� ����. remove, ��������� + recursive, ������������) � ����� ����� second-project � ��, ��� ��� ��������.


**�������� �����������**

 
1) ������� ������������� �������� � ��������� �� �������. ����� ������� �� ������� � ��������� ����� ������������ **(&&)**. 


2) � ������� ���� ����������� ������ � ����� � ����������� ���������� ���������. �� ��� ����� ������������ � ������� ������ �� ��������� ����� **(^)** � ���� **(v)**. 


3) ����� �� ������� �������� ����� ��� ����� ���������, ����� ������� ������ ������� ����� � ������ ������ **Tab**. ���� ���� ��� ����� ���� � ������� ����������, ��������� ������ ������� ���� ����. 
��������, �� ���������� � ����� dev. ������� ������� cd first � ������ ������� Tab. ���� ����� first-project ���� ������ dev, ��������� ������ ������������� ��������� � ���. ��������� ������ ������ Enter.


**������ � ��������� ������������**


*������������������ ��������:*


git init <br>
git add . <br>
git commit -m 'Your Commit Text' <br>
git push -u origin master <br>


**����� � ��������� ������������**


git clone 'your_repository_name' 