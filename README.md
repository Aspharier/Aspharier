<!-- Banner -->

<h1 align="center"> Hi there! 👋 Welcome to My GitHub Profile </h1>

<p align="center">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
</p>

## 🚀 About Me  
I'm **Ashish Singh**, a **Rookie Software Developer** passionate about **React-Native, Linux** and all things tech!  
I love building apps, optimizing code, and experimenting with new technologies.   

---

## ✨ Here's a small piece of code that represents me:  


```cpp
#include <iostream>
#include <vector>

class SoftwareDeveloper {
public:
    SoftwareDeveloper() {
        name = "Ashish Singh";
        role = "Rookie Software Developer";
        language_spoken = {"Hindi", "English"};
    }

    void say_hi() const {
        std::cout << "Thanks for dropping by, hope you find some of my work interesting." << std::endl;
    }

private:
    std::string name;
    std::string role;
    std::vector<std::string> language_spoken;
};

int main() {
    SoftwareDeveloper me;
    me.say_hi();
    return 0;
}
