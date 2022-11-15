<h1> Hi, I'm WorldWideGreg  <a href="https://myportfoliov2-beta.vercel.app/"><img src="https://myportfoliov2-beta.vercel.app/_next/image?url=%2F_next%2Fstatic%2Fmedia%2Flogo-light.ccf7db5f.png&w=64&q=75" width="30"/></a></h1>  

[![Twitter: Greg Morel](https://img.shields.io/twitter/follow/WorldWideGreg?style=social)](https://twitter.com/MorelGrgory1)
[![Linkedin: Greg Morel](https://img.shields.io/badge/-GregMorel-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gregory-morel/)](https://www.linkedin.com/in/gregory-morel/)  
  
  
<p><em> I'm a self-taught dev, tech lover, I totally love this world of creating things and tools that helps people, that makes things easier, faster or prettier!</em></p>  

```javascript
interface GregsNeedsAndMotivations {
  salary: SalaryTypes;
  insurance: InsuranceTypes;
  workEnvironment: WorkEnvironmentTypes;
  techStack: Techs[];
}

interface GregsValue {
  efficiency: EfficiencyTypes;
  productivity: ProductivityTypes;
  reliability: ReliabilityTypes;
  autonomy: AutonomyTypes;
  techSkills: string[];
  softSkills: string[];
}

function greg(hiringIncentives: GregsNeedsAndMotivations): GregsValue {
  const {salary, insurance, workEnvironment, techStack} = hiringIncentives;
  if (salary !== SalaryTypes.ADEQUATE || insurance !== InsuranceTypes.COMPETITIVE || workEnvironment !== WorkEnvironmentsTypes.ENGAGING) {
    return HeadHunterResponses.REFUSE;
  }

  return {
    efficiency: EfficiencyTypes.VERY,
    productivity: ProductivityTypes.VERY_PRODUCTIVE,
    reliability: ReliabilityTypes.VERY_RELIABLE,
    autonomy: AutonomyTypes.AUTONOMOUS,
    techSkills: [
      'TypeScript', 'JavaScript', 'Python', 'GitHub', 'ReactJS', 'NextJS'
    ],
    softSkills: [
      'self-taught', 'mature', 'detail-oriented', 'reliable', 'disponible' 
    ]
  }
}

const answer = greg({...WhatYouAsACompanyHaveToOffer});

console.log(answer);
}
```

Thanks Jp for this  :joy:
