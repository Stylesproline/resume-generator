# resume-maker



![Alt text](https://drive.google.com/uc?export=view&id=0B3XkfYbZArSfdTc4ZVV4X0V0UGc)

## Install

```bash
$ git clone https://github.com/u4bi-dev/resume-maker.git resume
```

```bash
$ npm install
```

## build

```bash
$ npm run build
```

##### resume.js

```html
<script src="https://cdn.rawgit.com/u4bi-dev/resume-maker/master/dist/resume.js"></script>
```
```javascript
var resume = new Resume(element);
resume.render(data); // HTTP Link , JSON Object, JSON String
```

##### JSON Rule
```json
{
    "header" : {
        "avatar" : "https://avatars2.githubusercontent.com/u/35291634?s=72&v=4",
        "name": "Stylesproline",
        "job" : "Frontend Developer",
        "bio" : "This is the executive summary.",
        "email" : "Stylesproline@gmail.com.net",
        "icon" : {
            "github"    : "https://github.com/Stylesproline/resume-generator",
            "linkdin"   : "https://github.com/Stylesproline/resume-generator",
            "facebook"  : "https://github.com/Stylesproline/resume-generator",
            "instagram" : "https://github.com/Stylesproline/resume-generator",
            "twitter"   : "https://github.com/Stylesproline/resume-generator",
            "website"   : "https://github.com/Stylesproline/resume-generator"
        }
    },
    "projects" : [
        {
            "name" : "Test Project 1",
            "link" : "https://github.com/",
            "date" : {
                "start" : "2017/09/06",
                "end"   : "2017/09/07"
            },
            "bio" : "Test Web Project"
        }
    ],
    "skills" : [
        { 
            "title" : "Programming Languages",
            "entry" : [
                "Test Languages 1",
                "Test Languages 2"
            ]
        }
    ],
    "experience" : [
        {
            "name" : "Test Company 1",
            "link" : "https://github.com/https://github.com/",
            "job"  : "Frontend Developer",
            "date" : {
                "start" : "2017/09/06",
                "end"   : "2017/09/07"
            },
            "address" : "Stylesproline, Vilnus",
            "bios" : [
                "Test Comment 1",
                "Test Comment 2"
            ]
        }
    ],
    "eduandcert" : {
        "edu" : [
            {
                "title" : "Test College",
                "link" : "https://github.com/",
                "name"  : "Test lang",
                "date" : {
                    "start" : "2017/09/06",
                    "end" : "2017/09/07"
                }
            }
            
        ],
        "cert" : [
            {
                "title" : "Test Campus",
                "link" : "https://github.com/",
                "name" : "Test lang",
                "date" : "2017/09/07"
            }
            
        ]
    },
    "footer" : {
        "live" : false
    }
}

```

## License
[MIT](LICENSE)
