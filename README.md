# hello-world
This is my first code
#include<stdio.h>
int main()
{
printf("hello world");
}//todat c++progrem
#define _CRT_SECURE_NO_WARNINGS 1
#include<iostream>
#include<string>
using namespace std;
int main()
{
	//struct student
//{
//	string name;
//	int age;
//	int score;
//};
	////利用指针访问结构体变量。
	//student s = {"jonny",18,90};
	//student *p=&s;
	////结构体指针可以通过->来访问结构体中的成员。
	//cout<<"姓名"<<p->name<<"年龄"<<p->age<<"成绩"<<p->score<<endl;
//结构体嵌套结构体
	/*struct student
{
	string name;
	int age;
	int score;
};
struct teacher
{
	int id;
	string name;
	int age;
	struct student stu;
};*/
	//teacher t;
	//t.id = 10000;
	//t.name = "老王";
	//t.age = 50;
	//t.stu.name = "小王";
	//t.stu.age = 18;
	//t.stu.score = 90;
	//cout<<"老师姓名："<<t.name<<"老师年龄:"<<t.age<<"老师工资:"<<t.id<<endl<<"学生姓名"<<t.stu.name
	//	<<"学生年龄"<<t.stu.age<<"学生成绩"<<t.stu.score<<endl;

	//结构体做函数参数：
//		struct student
//{
//	string name;
//	int age;
//	int score;
//};
//struct teacher
//{
//	int id;
//	string name;
//	int age;
//	struct student stu;
//};
//void printf1(struct teacher t)
//{
//	t.age = 100;
//	cout<<"值传递中老师姓名："<<t.name<<"老师年龄: "<<t.age<<"老师工资: "<<t.id<<endl<<"学生姓名： "<<t.stu.name
//		<<"学生年龄： "<<t.stu.age<<"学生成绩： "<<t.stu.score<<endl;
//};
//void printf2(struct teacher *p)
//{
//	p->age = 200;
//	cout<<"地址传递中老师姓名："<<p->name<<"老师年龄: "<<p->age<<"老师工资: "<<p->id<<endl<<"学生姓名： "<<p->stu.name
//		<<"学生年龄： "<<p->stu.age<<"学生成绩： "<<p->stu.score<<endl;
//};
//	struct teacher t;
//	t.id = 10000;
//	t.name = "老王";
//	t.age = 50;
//	t.stu.name = "小王";
//	t.stu.age = 18;
//	t.stu.score = 90;
//	cout<<"main函数中老师姓名："<<t.name<<"老师年龄: "<<t.age<<"老师工资: "<<t.id<<endl<<"学生姓名： "<<t.stu.name
//		<<"学生年龄： "<<t.stu.age<<"学生成绩： "<<t.stu.score<<endl;
//	/*printf1(t);*/
//	printf2(&t);
	system("pause");
}
