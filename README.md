# Hi there! 👋 Welcome to My GitHub Profile

I'm **Ashish Singh**, a **Rookie Software Developer** passionate about React-Native,C++,Linux.  
Here's a small piece of code that represents me:

<div align="center">
  <img src="https://s4.ezgif.com/tmp/ezgif-4ce946cf50b0c6.gif" width="300" alt="Coding GIF" align="right"/>
</div>

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
