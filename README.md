# Zophia Horvath

```cpp
// ==!==!==!==!==!==!== //
// Zophia Horvath       //
// Undergrad Research   //
// Created:             //
// 03/04/2026           //
// Updated:             //
// Life                 //
// ==!==!==!==!==!==!== //

#include "user.h"

int main()
{ 

    user Zophia = new user();
    
    Zophia.setName("Zophia Horvath");
    Zophia.setTitle("Researcher");
    Zophia.setEducationLevel(Education.UNDERGRAD);
    Zophia.setUniversity(Universities.Salisbury);
    
    Zophia.addSkills(5,
            {
                "Lifelong developer",
                "Enjoys a good headscratcher",
                "Sysadmin proficiency",
                "Energetic",
                "Leader"
            }
    );

    Zophia.setDescription("Hi! I'm Zophia, an undergraduate at Salisbury University! I have been studying programming to varying degrees for the past 12 years.");

    Zophia.assignDiscord("archaezalia", 478945907748896792);
    Zophia.assignCommunity("Shadow Valley");

    printf("%s", Zophia.fancystr());

    return 0;
}
```
