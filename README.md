```js
class Me {
    construct() {
        this.username = "usermauro";
        this.pronouns = "he/him";
        this.country = "Argentina";
        this.contact = "mauroncioci@gmail.com";

        this.skills = [];
        this.achievements = [];
    }

    learn(skill) {
        if (!this.skills.includes(skills) {
            this.skills.push(skill);
        }
    }

    unlock(achievement) {
        this.achievements.push(achievement);
    }
}

const me = new Me();

// languages
me.learn("JavaScript");
me.learn("C#");

// frontend
me.learn("React");
me.learn("Sass");
me.learn("Tailwind");
me.learn("Redux");
me.learn("MobX");
me.learn("Astro");
me.learn("Envoyer");

// backend
me.learn("Nodejs");
me.learn("Express");
me.learn("JWT");
me.learn("Envoyer");

// mobile
me.learn("App Store deployment");
me.learn("Google Play deployment");
me.learn("React Native");
me.learn("Gradle");
me.learn("Xcode");
me.learn("Firebase analytics");
me.learn("Push notifications");
me.learn("Bitrise");
me.learn("Codepush"); // deprecated

// databases
me.learn("PostgreSQL");
me.learn("MongoDB");
me.learn("Sequelize");
me.learn("Mongoose");

// infrastructure
me.learn("Linux");
me.learn("Sysadmin");
me.learn("Amazon Web Services");
me.learn("Docker");

// game development
me.learn("Unity");
me.learn("Netcode");

// hidden achievements
me.unlock("Fixed production on Friday");
me.unlock("Survived React Native upgrades");
me.unlock("Debugged without AI");
me.unlock("Have you tried turning it off and on again?");
me.unlock("It was the cache");
```
