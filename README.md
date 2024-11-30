<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=timeGradient&height=300&&section=header&text=👋HELLO%20WORLD&fontSize=90&fontAlign=50&fontAlignY=30&desc=I%20'm%20Pp3ng😁!&descAlign=50&descSize=30&descAlignY=60&animation=twinkling" />
</p>

<div align="center">
<p align="center">
    <a href="https://github.com/Pp3ng"><img src="https://img.shields.io/badge/status-updating-brightgreen.svg"></a>
  <img src="https://komarev.com/ghpvc/?username=pp3ng&label=Profile%20views&color=0e75b6&style=flat" alt="pp3ng" />
<a href="https://wakatime.com/@018b0b2d-ab3f-4d4d-941c-c52b8275e363"><img src="https://wakatime.com/badge/user/018b0b2d-ab3f-4d4d-941c-c52b8275e363.svg" alt="Total time coded since Oct 8 2023" /></a>
</p>

  <a href="https://github.com/Pp3ng?tab=followers">
    <img src="https://img.shields.io/github/followers/Pp3ng?label=Followers&style=social" alt="GitHub followers">
  </a>
  <img src="https://img.shields.io/github/stars/Pp3ng?label=Stars&style=social" alt="GitHub User's stars">
</div>

<div align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=&theme=nord&border=true" alt="Random Dev Quote"/>
</div>

<div align = "center">
 <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=6495ED&center=true&vCenter=true&width=435&lines=Welcome+to+my+coding+universe!;System+Programming+Enthusiast;Always+Learning+New+Things" alt="Typing SVG" />
</div>

---

## 🎯 Overview

```cpp
class Me final {
public:
    static constexpr std::string_view username = "pp3ng";
    static constexpr std::string_view name = "Luopeng Zhou";
    enum class Status { CODING, DEBUGGING, LEARNING, SLEEPING } current_status = Status::CODING;
    std::map<std::string_view, std::string_view> introduction = {
        {"Learning", "Computer Scinence & Engineering"},
        {"Hobby", "Billiards"},
        {"Motto", "Stay hungry, stay foolish"}
};
    void say_hi() const noexcept {
        std::cout << std::format(R"(
    Operator: {} (@{})
    Current Status: {}
    Introduction:
        - Learning: {}
        - Hobby: {}
        - Motto: {}
    Thanks for visiting my GitHub profile!
    Let's embark on some epic coding adventures together! 💻
        )",
            name, username,
            status_to_string(current_status),
            introduction.at("Learning"),
            introduction.at("Hobby"),
            introduction.at("Motto")
        );
    }
private:
    static constexpr const char* status_to_string(Status s) {
        switch(s) {
            case Status::CODING: return "Crafting Digital Magic ✨";
            case Status::DEBUGGING: return "Bug Hunting 🐛";
            case Status::LEARNING: return "Loading Knowledge 📚";
            case Status::SLEEPING: return "Compiling Dreams 💤";
        }
        return "Unknown";
    }
};

auto main() -> int {
    std::unique_ptr<Me> me = std::make_unique<Me>();
    me->say_hi();
    return EXIT_SUCCESS;
}
```

---

## ⌨️ Things I code with

<a href="https://happyhackingkb.com/" target="_blank">
  <img src="https://pp3ng.github.io/photos/hhkb.png" alt="Programming GIF">
</a>

| Property                     | Data                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **️📟 Programming Language** | <a href="https://www.open-std.org/jtc1/sc22/wg14/" target="_blank">![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)</a> <a href="https://isocpp.org/" target="_blank">![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)</a> <a href="https://developer.nvidia.com/cuda-zone" target="_blank">![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat&logo=nvidia&logoColor=white)</a> <a href="https://www.python.org/" target="_blank">![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)</a> <a href="https://www.gnu.org/software/bash/" target="_blank">![Shell](https://img.shields.io/badge/-Bash-444444?style=flat&logo=GnuBash)</a> <a href="https://golang.org/" target="_blank"> <a href="https://www.rust-lang.org/" target="_blank">![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)</a> |
| **🛠️ Tool**                 | <a href="https://www.docker.com/" target="_blank">![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=flat&logo=docker&logoColor=white)</a> <a href="https://git-scm.com/" target="_blank">![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)</a> <a href="https://www.vim.org/" target="_blank">![Vim](https://img.shields.io/badge/Vim-019733?style=flat&logo=vim&logoColor=white)</a> <a href="https://github.com/tmux/tmux" target="_blank">![tmux](https://img.shields.io/badge/tmux-1BB91D?style=flat&logo=tmux&logoColor=white)</a>                                                                                                                                                                                                                                                                                                                                                                              |

## 📖 Things I Want to Learn

| Property                  | Data                                                                                                                                                                                                                                                                                                             |
|---------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **🔐 Network Security**   | <a href="https://www.openssl.org/" target="_blank">![OpenSSL](https://img.shields.io/badge/OpenSSL-FF8C00?style=flat&logo=openssl&logoColor=white)<a href="https://www.wireshark.org/" target="_blank">![Wireshark](https://img.shields.io/badge/Wireshark-1679A8?style=flat&logo=wireshark&logoColor=white)</a> |
| **📱 Mobile Development** | <a href="https://flutter.dev/" target="_blank">![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)</a> <a href="https://swift.org/" target="_blank">![Swift](https://img.shields.io/badge/Swift-F05138?style=flat&logo=swift&logoColor=white)</a>                    |
| **🖼️ Computer Graphics** | <a href="https://www.opengl.org/" target="_blank">![OpenGL](https://img.shields.io/badge/OpenGL-FFFFFF?style=flat&logo=opengl)</a>                                                                                                                                                                               |

---

## 🌟 Representative Repositories

<div align="center">
  <a href="https://github.com/Pp3ng/blitz_logger">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Pp3ng&repo=blitz_logger&theme=vue" alt="PGS Repository" />
  </a>
  <a href="https://github.com/Pp3ng/webCpp">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=Pp3ng&repo=webCpp&theme=vue" alt="webCpp Repository" />
  </a>
</div>

---

## 😎 Bits & Bytes of Me

- 🖥️ Customization enthusiast for development environments
- 🎱 Calculating angles in both code and billiards
- 📚 Always reading about new technologies and system internals
- 🎮 Retro gaming and pixel art lover
- ☕️ Powered by coffee and curiosity
- 🌱 Constant learner and knowledge sharer
- 🙆‍♂️ 100+ WPM typer using Vim keybindings!

```bash
PLAYER: PP3NG
LEVEL: 25
CLASS: System Programmer

STATS:
━━━━━━━━━━━━━━━━━━━━━━━━
Vim:        [⭐⭐⭐⭐⭐] 95/100
C/C++:      [⭐⭐⭐⭐ ] 85/100
Billiards:  [⭐⭐⭐⭐ ] 80/100

ACTIVE BUFFS:
• Coffee Boost (+20% Coding Speed)
• Vim Power (+30% Text Editing)
• Pool Focus (+25% Concentration)

```

---

## 📈 Statistics

<div align="center">
    <img src="https://github-readme-stats.vercel.app/api/wakatime?username=Pp3nG&layout=compact&theme=vue&langs_count=10&hide=other,text" alt="My's WakaTime stats"/>
</div>

<div align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=pp3ng&show_icons=true&theme=vue&include_all_commits=true&count_private=true&rank_icon=github"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pp3ng&layout=compact&langs_count=8&theme=vue&text_bold=true"/>
</div>

<div align="center">
  <img width="95%" src="https://github-readme-streak-stats.herokuapp.com/?user=pp3ng&theme=vue" alt="pp3ng" />
</div>
<img width="800" src="https://github-readme-activity-graph.vercel.app/graph?username=Pp3ng&theme=github-compact&hide_border=true&area=true&custom_title=Contribution%20Graph" />

---

## 🏆 GitHub Trophies

<p align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=pp3ng&theme=vue&column=4&margin-w=15&margin-h=15" alt="pp3ng" />
  </a>
</p>

---

### 🎵 Vibing To

<div align ="center">
  <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=31xzhprryykgscfigdpz47ci7plm&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false)](https://github.com/kittinan/spotify-github-profile" />

 </div>

---

## 🎉 Random dev joke for you

<div align="center">
<img src="https://readme-jokes.vercel.app/api?theme=vue" alt="Jokes Card" />
</div>

---

## 🤝 Let's Connect and Collaborate!

I'm always open to interesting conversations and collaboration opportunities. Whether you want to discuss a project,
share ideas, or just chat about technology, feel free to reach out!


<div align="center">
  <a href="https://x.com/Pp3ng_" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/X-1DA1F2?style=flat&logo=x&logoColor=black" alt="X (formerly Twitter)">
  </a>
  <a href="https://www.instagram.com/pp3ng___" target="_blank" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="mailto:pp3ng@outlook.com" style="margin: 0 10px;">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email">
  </a>
</div>
<p align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=150&color=gray&section=footer&reversal=false&textBg=false">
</p>
