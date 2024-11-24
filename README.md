<h1 align="center">
Hi, I'm Marc Morales!
<a href="https://github.com/Mmorales87" target="_self">
		<img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30">
	</a>
</h1>
<p align="center">
	<a href="https://github.com/Mmorales87">
		<img src="https://komarev.com/ghpvc/?username=mmorales87&label=Profile%20views&color=fea116&style=flat" alt="mmorales87" />
	</a>
</p>
<br/>
<p align="center">
	<a href="https://github.com/Mmorales87">
		<img src="https://readme-typing-svg.herokuapp.com?lines=Developer;Freelancer;Jodie's%20🐕%20Father;Flutter%20lover❤️;Always%20learning%20new%20things&center=true&width=380&height=45">
	</a>
</p>

```dart
import 'package:flutter/passion.dart'; // Because passion is what fuels my Flutter apps
import 'package:flutter/material.dart';

class BioScreen extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    final bio = getBio();

    return Scaffold(
      appBar: AppBar(
        title: Text('Developer Bio'),
      ),
      body: ListView.builder(
        itemCount: bio.keys.length,
        itemBuilder: (context, index) {
          final key = bio.keys.elementAt(index);
          final value = bio[key];
          return ListTile(
            title: Text('$key'),
            subtitle: Text('$value'),
          );
        },
      ),
    );
  }

  Map<String, String> getBio() {
    return {
      '- ⚡ Quick bio:': 'I am a passionate Full Stack Developer with a focus on building impactful applications.🚀',
      '- 🎓 Education:': 'I hold a Higher Degree in Multiplatform Application Development.',
      '- 🔭 I’m currently working on': 'Full Stack Developer at [3ipunt](https://www.3ipunt.com), focusing on innovative educational solutions.',
      '- 🚀 Personal Projects:': 'Currently developing Runekt, an app for runners, and building a CRM to expand OnTheBeat with more advanced features.',
      '- 🌱 I’m currently learning': 'Advanced Flutter techniques, state management, and diving deeper into testing frameworks',
      '- 👯 I’m looking to collaborate on': 'Flutter applications that enhance user experience and solve real-world problems',
      '- 🤔 I’m looking for help with': 'Exploring best practices for large-scale app testing and architecture in Flutter',
      '- 💬 Ask me about': 'Flutter, PHP, JavaScript, Angular, and digital solutions for modern challenges',
      '- 🌟 Fun fact:': 'I believe every great app starts with a hot reload 🔥. Flutter makes it happen in real-time!',
    };
  }
}
```

<hr>


## Connect with me ☕
<p align="center">
	<a href="mailto:moralesgarciamarc@gmail.com"><img img src="https://img.shields.io/badge/gmail-%23EA4335.svg?style=plastic&logo=gmail&logoColor=white" alt="Gmail"/></a>
	<a href="https://linkedin.com/in/marc-mg"><img src="https://img.shields.io/badge/Linkedin-%230077B5.svg?style=plastic&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
	<a href="https://github.com/Mmorales87"><img src="https://img.shields.io/badge/github-%23181717.svg?style=plastic&logo=github&logoColor=white" alt="GitHub"/></a>
	<a href="https://stayandcode.com/"><img src="https://img.shields.io/badge/website-000000?style=plastic&logo=About.me&logoColor=white" alt="stayandcode"/></a>
</p>

<h2 align="left">Languages and Tools</h2>

<table align="center">
  <tr>
    <th>Programming Languages</th>
    <th>Frontend</th>
    <th>Backend</th>
  </tr>
  <tr>
    <td align="center">
      <a href="https://www.java.com" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" width="40" height="40"/>
      </a>
      <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
      </a>
      <a href="https://www.typescriptlang.org/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>
      </a>
      <a href="https://www.php.net" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/>
      </a>
    </td>
    <td align="center">
      <a href="https://angular.io" target="_blank" rel="noreferrer">
        <img src="https://angular.io/assets/images/logos/angular/angular.svg" alt="angular" width="40" height="40"/>
      </a>
      <a href="https://getbootstrap.com" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/>
      </a>
      <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>
      </a>
    </td>
    <td align="center">
      <a href="https://nodejs.org" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/>
      </a>
    </td>
  </tr>
  <tr>
    <th>Mobile Apps</th>
    <th>Database</th>
    <th>DevOps</th>
  </tr>
  <tr>
    <td align="center">
      <a href="https://flutter.dev" target="_blank" rel="noreferrer">
        <img src="https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=fff" alt="flutter"/>
      </a>
      <a href="https://developer.android.com" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/android/android-original-wordmark.svg" alt="android" width="40" height="40"/>
      </a>
    </td>
    <td align="center">
      <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/>
      </a>
      <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
      </a>
      <a href="https://www.postgresql.org" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/>
      </a>
    </td>
    <td align="center">
      <a href="https://aws.amazon.com" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" alt="aws" width="40" height="40"/>
      </a>
    </td>
  </tr>
  <tr>
    <th>Software</th>
    <th>Others</th>
  </tr>
  <tr>
    <td align="center">
      <a href="https://www.figma.com/" target="_blank" rel="noreferrer">
        <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/>
      </a>
      <a href="https://postman.com" target="_blank" rel="noreferrer">
        <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/>
      </a>
      <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/>
      </a>
      <a href="https://www.blender.org/" target="_blank" rel="noreferrer">
        <img src="https://download.blender.org/branding/community/blender_community_badge_white.svg" alt="blender" width="40" height="40"/>
      </a>
    </td>
    <td align="center">
      <a href="https://git-scm.com/" target="_blank" rel="noreferrer">
        <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/>
      </a>
      <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer">
        <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/>
      </a>
      <a href="https://www.linux.org/" target="_blank" rel="noreferrer">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/>
      </a>
    </td>
  </tr>
</table>
<br>

<hr>

<p><img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=mmorales87&show_icons=true&text_color=f0f0f0&bg_color=171717&locale=en&layout=compact" alt="mmorales87" /></p>
<br>

<p align="left"> <a href="https://github.com/ryo-ma/github-profile-trophy"><img src="https://github-profile-trophy.vercel.app/?username=mmorales87" alt="mmorales87" /></a> </p>
<br>
<br>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=mmorales87&show_icons=true&locale=en" alt="mmorales87" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=mmorales87&theme=dark" alt="mmorales87" /></p>

<h4 align="center">Visitor's count :eyes:</h4>

<p align="center"><img src="https://profile-counter.glitch.me/{Mmorales87}/count.svg" alt="Mmorales87 :: Visitor's Count" /></p>
