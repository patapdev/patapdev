### Hi there 👋 im pat

<!--
**pat1221/pat1221** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

  public class pat extends male implements Gamer, Developer {

	@Override
	public String getName() {
		return "patrick";
	}
	
	@Override
	public List<String> getAliases() {
		return Arrays.asList("pat", "patap");
	}

        public Pace() {
        super("Pat", "Australia");

        this.addLanguage("Java");
        this.addExperience("2 Years(java)");
     }
   }

	@Override
	public String aboutme() {
		return "i enjoy gaming" +
		"\n" + "I like to code Java";
	}
    
	
} 


public abstract class Human {

  @Getter private final String username;
  @Getter private final String country;

  private Set<String> languages = new HashSet<>();
  private Set<String> experiences = new HashSet<>();

  public GitHubUser(String username, String country) {
      this.name = username;
      this.country = country;
  }

  public void addLanguage(String... language) {
      this.languages.addAll(language);
  }
  
  public void addExperience(String... experience) {
      this.experiences.addAll(experience);
  }
}

