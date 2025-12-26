// src/portfolio.js

// 1. Personal Greeting
const greeting = {
  title: "Abu Zobayer",
  logo_name: "Abu Zobayer",
  nickname: "Zobayer",
  subTitle:
    "Doctoral Instructional Assistant at Texas State University specializing in Epidemic Modeling, Evolutionary Game Theory, and Mathematical Biology.",
  resumeLink:
    "https://github.com/sajjadzobayer52-droid/Abu-Zobayer/raw/main/CV_%20ABU%20ZOBAYER......pdf", // Link to your uploaded CV
  portfolio_repository: "https://github.com/sajjadzobayer52-droid/Abu-Zobayer",
  githubProfile: "https://github.com/sajjadzobayer52-droid",
};

// 2. Technical Skills (from your CV)
const skills = {
  data: [
    {
      title: "Mathematics & Modeling",
      fileName: "MathsImg",
      skills: [
        "⚡ Proficiency in MATLAB and MATHEMATICA for research modeling.",
        "⚡ Expertise in Epidemic models and Evolutionary Game Theory (EGT).",
        "⚡ Experience in data-driven modeling and Nipah virus transmission research."
      ],
      softwareSkills: [
        { skillName: "MATLAB", fontAwesomeClassname: "logos:matlab" },
        { skillName: "Python", fontAwesomeClassname: "logos:python" },
        { skillName: "C++", fontAwesomeClassname: "logos:c-plusplus" },
      ],
    },
  ],
};

// 3. Professional Experience
const degrees = {
  degrees: [
    {
      title: "Texas State University",
      subtitle: "Ph.D. in Mathematics (In Progress)",
      logo_path: "txstate_logo.png",
      alt_name: "TXST",
      duration: "2025 - Present",
      descriptions: [
        "⚡ Serving as a Doctoral Instructional Assistant in the Department of Mathematics."
      ],
    },
    {
      title: "Bangladesh University of Engineering and Technology (BUET)",
      subtitle: "M.Sc. in Mathematics",
      logo_path: "buet_logo.png",
      alt_name: "BUET",
      duration: "2021 - 2023",
      descriptions: [
        "⚡ Completed thesis on epidemic modeling and social awareness behavior."
      ],
    }
  ],
};
