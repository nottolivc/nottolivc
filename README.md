# <div align="center">About Andrew</div>  
### <div align="center">Full Stack Software Engineer 💻 </div> 
<div align="center">
<!-- Need to get in touch? Find Andrew on <a href="https://linkedin.com/in/andrew-speer">LinkedIn <br /> -->
<!-- <img src=https://img.shields.io/badge/linkedin-%231E77B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white alt=linkedin style="margin-bottom: 5px;" /></a> -->
</div>
<br/>  

### Current Tech: 
<table><tr><td valign="top" width="33%">

### Frontend  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="React" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/bootstrap-plain.svg" alt="Bootstrap" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/redux-original.svg" alt="Redux" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/typescript-original.svg" alt="TypeScript" height="50" />  
</div>

</td><td valign="top" width="33%">

### Backend  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="JavaScript" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/mongodb-original-wordmark.svg" alt="MongoDB" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nodejs-original-wordmark.svg" alt="Node.js" height="50" />  
<!-- <img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/nginx-original.svg" alt="Nginx" height="50" />   -->
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/express-original-wordmark.svg" alt="Express.js" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/postgresql-original-wordmark.svg" alt="
                                                                                                                    greSQL" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/typescript-original.svg" alt="TypeScript" height="50" />  
</div>

</td><td valign="top" width="33%">


### Other Tech  
<div align="center">  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/linux-original.svg" alt="Linux" height="50" />  
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="50" />  
</div>

</td></tr></table>  

<br/>

### Experienced in (and currently working with) the following:

- TypeScript, JavaScript, Python, Go
- React.js, Node.js, RESTful & GraphQL, MVCs, Express.js, Next.js
- AWS, Cloud Architecture & Computing
- PostgreSQL, SQL, NoSQL, ORMs
- Machine Learning & Neural Networks
<br />

<em>Always up for learning/working with new teams and technologies</em>
<br />
<em>Certified Credentals for Software Engineering by Triplebyte: </em>
<!-- <a href="https://triplebyte.com/tb/andrew-speer-cpwmfrq/certificate/track/frontend"></a> -->
<br />
<a href="https://triplebyte.com/tb/andrew-nottoli-6tkx0yz/certificate"> Credential </a>
<br />

## SOLID Design in React
```
const Data = {
  value: "SOLID in React",
  color: "blue",
  format: (value) => value.toUpperCase(),
  validate: (value) => value.length > 0
};

// S - Single Responsibility Principle
// Component with a single responsibility: Display the value.
const DisplayData = ({ value }) => <div>{value}</div>;

// O - Open/Closed Principle
// Component that can display data in a color without changing its internal structure.
const ColorfulData = ({ value, color }) => <div style={{ color }}>{value}</div>;

// L - Liskov Substitution Principle
// Base and derived functions to demonstrate substitutability.
function baseFormat(value) {
  return value;
}

function extendedFormat(value) {
  return value.toLowerCase();
}

// I - Interface Segregation Principle
// Seperate out functionalities into different methods.
const formatData = (value, formatter) => formatter(value);
const validateData = (value, validator) => validator(value);

// D - Dependency Inversion Principle
// Components depending on abstractions (props) rather than concrete implementations.
const DataWrapper = ({ value, formatter, validator }) => {
  const formattedValue = formatData(value, formatter);
  const isValid = validateData(value, validator);

  return (
    <div>
      {isValid ? formattedValue : "Invalid Data"}
    </div>
  );
};

const SOLIDComponent = () => {
  return (
    <div>
      <DisplayData value={Data.value} />
      <ColorfulData value={Data.value} color={Data.color} />
      <DataWrapper 
        value={Data.value} 
        formatter={extendedFormat} 
        validator={Data.validate} 
      />
    </div>
  );
};

export default SOLIDComponent;
```

<!-- ### GitHub Profile -->
<!-- <div align="center">
  
<a href="https://github.com/nottolivc" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
</div>  
  

<br/>  

<div align="center"><img src="https://github-readme-stats.vercel.app/api?username=nottolivc&show_icons=true&count_private=true&hide_border=true&theme=react" align="center" style="width: 100%" /> 

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nottolivc&hide_border=true&layout=compact&langs_count=8&theme=react&hide_border=true" align="center" style="width: 100%" />  
</div> 
<br/>   -->

<!--
**nottolivc/nottolivc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
