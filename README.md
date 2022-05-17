### Alex Krueger

|Subject|Contents|
|-----|-----|
|name:string|"Alex"|
|university:string|"University of Illinois at Chicago"|
|coding_graduate_from:string|"Actualize Coding Bootcamp"|
|graduated:datetime|DateTime.new(2022,3,25)|
|introduction:string|"Hi, I'm Alex. I'm a certified nerd offering an abnormal perspective including music theory 🎵, axe throwing 🪓, and esports production 🎥"|

Alex has_many Backgrounds

```
Backgrounds.create!([
  {
    title: "Teaching Assistant", 
    organization: "Actualize Coding Bootcamp", 
    years: 1
  },
  {
    title: "Tournament Administrator and Broadcast Manager", 
    organization: "ESL", 
    years: 1
  },
  {
    title: "Axe Throwing Coach & Floor Manager", 
    organization: "Backyard Axe Throwing League", 
    years: 4
  },
  {
    title: "Musician",
    organization: "Various",
    years: 3
  }
])
```

Alex has_many Projects

```
Projects.create!([
  {
    name: "practAxe", 
    short_description: "An axe-throwing app made for keeping track of your training sessions!", 
    currently_working_on: true, 
    deployed: false
  },
  {
    name: "Cows are Friends", 
    short_description: "A restaurant review website made specifically for vegetarians and vegans.", 
    currently_working_on: false, 
    deployed: true
  }
])
```
