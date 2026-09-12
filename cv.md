# Anhelina Makhotkina

## Contact Information

* **Email:** [gеlyamakh@gmail.com](mailto:grlyamalh@gmail.com)
* **GitHub:** https://github.com/makhotkinaangelina
* **Telegram:** https://t.me/makhotkinaangelina
* **Discord:** makhotkinaangelina

## About Me

Software Engineer with 1+ year of professional experience in software development. I am interested in Full-Stack and AI Engineering, with hands-on experience in web development, automation, databases, REST APIs, and AI-powered solutions.

I enjoy learning new technologies, solving practical problems, and turning ideas into working software. I am looking to deepen my engineering skills and contribute to challenging real-world projects.

## Skills

* **Programming Languages:** JavaScript, TypeScript, SQL
* **Frontend:** React, Next.js, HTML, CSS, MUI
* **Backend & APIs:** Node.js, REST API
* **Databases:** PostgreSQL, Supabase
* **AI & Automation:** OpenAI API, n8n, RAG, Embeddings, Vector Search
* **Tools & Infrastructure:** Git, GitHub, Docker, Windows Server

## Code Example

**Human readable duration format — Codewars, 4 kyu**

```javascript
function formatDuration (seconds) {
  const formats = [
    { word: " year",
      value: 31536000,
      amount: 0,},
    { word: " day",
      value: 86400,
      amount: 0,},
    { word: " hour",
      value: 3600,
      amount: 0,},
    { word: " minute",
      value: 60,
      amount: 0,},
    { word: " second",
      value: 1,
      amount: 0,}
  ]; 

  let filledFormats = [];
  let tmp;
  let result = "";

  for (let i = 0; i < 5; i++) {
    tmp = Math.floor(seconds / formats[i].value);
    seconds = seconds % formats[i].value;
    formats[i].amount = tmp;
    if (tmp) {
      filledFormats.push(i);
      if (tmp > 1) {
        formats[i].word += "s";
      }
    }
  }

  switch (filledFormats.length) {
    case 0: result = "now"; break;
    case 1: result = `${formats[filledFormats[0]].amount + formats[filledFormats[0]].word}`; break;
    case 2: result = `${formats[filledFormats[0]].amount + formats[filledFormats[0]].word + " and " + formats[filledFormats[1]].amount + formats[filledFormats[1]].word}`; break;
    case 3: result = `${formats[filledFormats[0]].amount + formats[filledFormats[0]].word + ", " + formats[filledFormats[1]].amount + formats[filledFormats[1]].word + " and " + formats[filledFormats[2]].amount + formats[filledFormats[2]].word}`; break;
    case 4: result = `${formats[filledFormats[0]].amount + formats[filledFormats[0]].word + ", " + formats[filledFormats[1]].amount + formats[filledFormats[1]].word + ", " + formats[filledFormats[2]].amount + formats[filledFormats[2]].word + " and " + formats[filledFormats[3]].amount + formats[filledFormats[3]].word}`; break;
    case 5: result = `${formats[filledFormats[0]].amount + formats[filledFormats[0]].word + ", " + formats[filledFormats[1]].amount + formats[filledFormats[1]].word + ", " + formats[filledFormats[2]].amount + formats[filledFormats[2]].word + ", " + formats[filledFormats[3]].amount + formats[filledFormats[3]].word + " and " + formats[filledFormats[4]].amount + formats[filledFormats[4]].word}`; break;
  }
 
  return result;
}
```

[View solution on Codewars](https://www.codewars.com/kata/52742f58faf5485cae0000b9)

## Experience

### Software Engineer

**1+ year of professional experience**

* Developed and maintained frontend applications using React and Next.js.
* Designed and implemented n8n workflows for process automation and AI-powered solutions.
* Developed REST API endpoints and integrated external services, including OpenAI API.
* Worked extensively with PostgreSQL and SQL, including CRUD operations, database indexing, and data processing.
* Worked with RAG solutions using embeddings and vector search.
* Used Docker for application development and deployment, including writing Dockerfiles.
* Worked with Git and GitHub in a collaborative development environment.

## Education

### Belarusian State University of Informatics and Radioelectronics (BSUIR)

**Automated Information Processing Systems**
2021–2025

## Languages

* **Russian:** Native
* **Belarusian:** Native
* **English:** B2+
* **German:** B1
