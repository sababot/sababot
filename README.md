# sababot

![visitors](https://visitor-badge.laobi.icu/badge?page_id=zhenye-na.zhenye-na)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)](https://github.com/ellerbrock/open-source-badge/)
![alt text](https://www.codewars.com/users/sababot/badges/large)

```c++
#include <iostream>
#include <string>
#include <vector>

using namespace std;

class Personality
{
  string name;
  vector<string> languages = {};
  vector<string> interests = {};
  bool loveOpenSource;
};   

int main()
{
  Personality me;
  
  me.name = "sababot";
  me.languages = {"C++", "C#", "Python", "HTML", "CSS"}
  me.interests = {"BitcoinAlgorithm", "Cryptography", "C++", "Linux", "Parkour", "Sports"}
  me.loveOpenSource = true;
  
  return 0;
}
