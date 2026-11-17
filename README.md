```cpp
// !==!==!==!==!==!==!==!==!==! //
// Zophia-Monarch Horvath       //
// Undergrad Student            //
// Created:                     //
// 03/04/2026                   //
// Updated:                     //
// 11/17/2026                   //
// !==!==!==!==!==!==!==!==!==! //

#include "user.h"
using namespace std;

int main()
{ 

    user Zophia_Monarch = new user();
    
    Zophia_Monarch.setName("Zophia-Monarch Horvath");
    Zophia_Monarch.setEducationLevel(Education.UNDERGRAD.JUNIOR);
    Zophia_Monarch.setUniversity(Universities.Salisbury);
    
    Zophia_Monarch.addSkills(4,
            {
                "Enjoys a good headscratcher",
                "Sysadmin proficiency",
                "Energetic",
                "Leader"
            }
    );

    Zophia_Monarch.setDescription("Hi! I'm Zophia, an undergraduate at Salisbury University!" +
"I have been studying programming to varying degrees for the past 14 years.");

    Zophia_Monarch.assignDiscord("archaezalia", 478945907748896792);

    printf("%s", Zophia_Monarch.fancystr());

    return 0;
}
```
![GitHub Stats Card](https://ghstats.dev/api/card?username=zophiale&theme=ayu)
