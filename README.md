```java
public class AboutMe {
    public static void main(String[] args) {
        AboutMe aboutMe = new AboutMe();
        Profile resume = aboutMe.assembleResume();
        System.out.println(resume);
    }

    public Profile assembleResume() {
        List<String> personalInformation = personalInformation();
        List<String> skillsList = skills();
        List<String> professionalExperience = professionalExperience();

        Profile profile = new Profile();
        profile.setPersonalInformation(personalInformation);
        profile.setSkills(skillsList);
        profile.setProfessionalExperience(professionalExperience);

        return profile;
    }

    private List<String> personalInformation() {
        List<String> information = new ArrayList<>();
        String name = "Stephanie Tessari dos Santos";
        String area = "Software Development";
        String work = "Sifat Sistemas";
        String city = "São José do Rio Preto - SP, Brazil";
        List<String> goals = Arrays.asList(
            "Acquire new knowledge every day",
            "Working in a company with agile methodologies like SCRUM",
            "Having the opportunity to travel while working remotely",
            "Reaching the role of CTO"
        );

        information.add(name);
        information.add(area);
        information.add(work);
        information.add(city);
        information.addAll(goals);

        return information;
    }

    private List<String> skills() {
        List<String> skills = new ArrayList<>();
        List<String> languages = Arrays.asList("Java", "SQL");
        List<String> frameworks = Arrays.asList("Spring Boot", "Hibernate");
        List<String> tools = Arrays.asList("Postman", "IntelliJ", "HeidiSQL", "GitLab", "Jira");

        skills.addAll(languages);
        skills.addAll(frameworks);
        skills.addAll(tools);

        return skills;
    }

    private List<String> professionalExperience() {
        return Arrays.asList(
            "Rest API development",
            "Migration from monolithic system to microservices",
            "Elaboration of tasks using Jira"
        );
    }

    public static class Profile {
        private List<String> personalInformation;
        private List<String> skills;
        private List<String> professionalExperience;

        @Override
        public String toString() {
            return "Personal Information: " + personalInformation +
                "\nSkills: " + skills +
                "\nProfessional Experience: " + professionalExperience;
        }}
}
```
<br> 
<a href="https://github.com/Gurupreet">
  <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SteTessari&theme=dracula&hide_langs_below=1" />
</a>

<a href="https://github.com/Gurupreet">
 <img align="center" src="https://github-readme-stats.vercel.app/api?username=SteTessari&show_icons=true&theme=dracula&line_height=27" alt="**STEPHANIE TESSARI** github stats"/>
</a>

<br> 

  <a href="https://www.linkedin.com/in/stephanie-tessare-86ba30192/" alt="LinkedIn">
    <img src="https://img.shields.io/badge/-Linkedin-0e76a8?style=flat-square&logo=Linkedin&logoColor=white" />
  </a>

  <a href="https://api.whatsapp.com/send?phone=5511976612807" alt="WhatsApp">
    <img src="https://img.shields.io/badge/-WhatsApp-25d366?style=flat-square&labelColor=25d366&logo=whatsapp&logoColor=white" />
  </a>
</p>
