### Hi there 👋 im pat

  public class pat1221 extends Boy implements Gamer, Developer {

	@Override
	public String getName() {
		return "patrick";
	}
	
	@Override
	public List<String> getAliases() {
		return Arrays.asList("Pace", "PaceSomesh");
	}

        public Pace() {
        super("Pace", "India");

        this.addLanguage("Java");
        this.addExperience("2 Years(java)");
     }
    }

	@Override
	public String aboutme() {
		return "I like to play video games" +
		"\n" + "I like to code Java";
	}
    
	@Override
	public void codingStuff() {
		String[] learning = ["Java", "Node.js / Discord.js", "Python"];
		String tryingTo = "Make good GUIs in minecraft clients /plugins /mods";
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
```
<div align="center">
	
![pat1221's GitHub stats](https://github-readme-stats.vercel.app/api?username=pat1221&show_icons=true&theme=vision-friendly-dark)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=pat1221)](https://github.com/anuraghazra/github-readme-stats)
