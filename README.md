








import java.time.LocalDate;
import java.util.List;

public class AboutMe {


    private String introduction;
    private String firstName;
    private String lastName;
    private List<String> hobbies;
    private LocalDate myBirthdate;
    private String  howToReachMe;

    public AboutMe() {
    }

    public String getIntroduction() {
        return "Hi I'm alb3rtsk21 ";
    }

    public String getFirstName() {
        return "Albert";
    }
    public String getLastName() {
        return "Vasile";
    }
    public List<String> getHobbies() {
        return List.of("Read Manga","Watch Anime","Learn Programming");
    }


    public LocalDate getMyBirthdate() {
        return LocalDate.of(2002,5,15);
    }

    public String getHowToReachMe() {
        return "email: albertvalentin.2002@gmail.com";
    }


    public void setFirstName(String firstName) {
        this.firstName = firstName;
    }

    public void setLastName(String lastName) {
        this.lastName = lastName;
    }

    public void setHobbies(List<String> hobbies) {
        this.hobbies = hobbies;
    }

    public void setMyBirthdate(LocalDate myBirthdate) {
        this.myBirthdate = myBirthdate;
    }

    public void setHowToReachMe(String howToReachMe) {
        this.howToReachMe = howToReachMe;
    }
}
