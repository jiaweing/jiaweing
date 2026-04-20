<!-- Intro  -->
```
    ___  ___  ________          ___       __   _______   ___          ________   ________     
   |\  \|\  \|\   __  \        |\  \     |\  \|\  ___ \ |\  \        |\   ___  \|\   ____\    
   \ \  \ \  \ \  \|\  \       \ \  \    \ \  \ \   __/|\ \  \       \ \  \\ \  \ \  \___|    
 __ \ \  \ \  \ \   __  \       \ \  \  __\ \  \ \  \_|/_\ \  \       \ \  \\ \  \ \  \  ___  
|\  \\_\  \ \  \ \  \ \  \       \ \  \|\__\_\  \ \  \_|\ \ \  \       \ \  \\ \  \ \  \|\  \ 
\ \________\ \__\ \__\ \__\       \ \____________\ \_______\ \__\       \ \__\\ \__\ \_______\
 \|________|\|__|\|__|\|__|        \|____________|\|_______|\|__|        \|__| \|__|\|_______|

```
```python
from typing import List, Dict, Tuple


class jiaweing:
    """
    software engineer · designer · founder
    creating unique and original digital experiences
    """

    def __init__(self):
        self.name      = "Jia Wei Ng"
        self.alias     = "Jay"
        self.age       = 25
        self.location  = "Singapore"
        self.website   = "https://jiaweing.com"

    @property
    def bio(self) -> str:
        return (
            "just an ordinary guy building software.\n"
            "a designer and software engineer crafting unique, and original digital experiences.\n"
            "drawn to psychology, space, quantum mechanics, and the strange phenomena that shape the universe."
        )

    @property
    def setup(self) -> Dict[str, object]:
        return {
            "workstation": {
                "processor": "i7-14700KF",
                "gpu"      : "RTX 4070 Ti SUPER",
                "ram"      : "32GB DDR5",
            },
            "laptop"     : "MacBook Air M2 Midnight",
            "peripherals": [
                "Yunzii AL75 Keyboard",
                "AULA F75 Pro",
                "Shure SM7B + Focusrite Scarlett 2i2",
                "Fujifilm X-T50 + Sigma 18-50mm f2.8",
            ],
        }

    @property
    def contact(self) -> Tuple[str, str, str, str, str]:
        github   = "github.com/jiaweing"
        linkedin = "linkedin.com/in/jiaweing"
        twitter  = "x.com/j14wei"
        youtube  = "youtube.com/@j14wei"
        email    = "hey@jiaweing.com"

        return github, linkedin, twitter, youtube, email


jay = jiaweing()
```

### selected projects

#### [dropdrawer](https://github.com/jiaweing/DropDrawer) [![GitHub stars](https://img.shields.io/github/stars/jiaweing/DropDrawer?style=flat&color=yellow)](https://github.com/jiaweing/DropDrawer/stargazers)
responsive shadcn/ui dropdown-to-drawer component
