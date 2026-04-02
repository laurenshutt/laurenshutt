# Hi! I’m Lauren

```js
const config = {
  name: "Lauren",
  role: "Web Developer",
  location: "Virginia",

  vibe: "minimal, playful, intentional",

  caresAbout: [
    "microinteractions",
    "spacing",
    "naming things properly"
  ],

  avoids: [
    "clutter",
    "loud design",
    "unnecessary complexity"
  ],

  techStack: {
    frontend: ["JavaScript", "CSS", "HTML"],
    tools: ["Git", "Figma", "GSAP"],
    environment: ["VSCode", "Adobe Experience Manager", "WordPress"]
  },

  currentFocus: "building things that feel good to use",

  knownFor: [
    "over-refactoring perfectly fine code",
    "renaming variables 12 times",
    "noticing when 1px is off"
  ]
};

class Human {
  constructor(config) {
    Object.assign(this, config);
    this.bugsFixed = 0;
    this.state = "idle";
  }

  code() {
    this.bugsFixed++;
    return "interfaces that feel calm, intentional, and slightly magical";
  }

  overthink() {
    return true;
  }
}

const lauren = new Human(config);
lauren.code();
```
