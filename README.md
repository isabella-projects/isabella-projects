<div align="left">
    <a href="https://github.com/isabella-projects/">
        <img src="https://i.imgur.com/YlGrpaq.png" width="800px" height="auto"><br>
    </a>
</div>
<div align="left">
    <img src="https://komarev.com/ghpvc/?username=isabella-projects&label=Profile%20views&color=brightgreen&style=flat&abbreviated=true" alt="isabella-projects" />
</div>

```php
class Developer
{
    public static function introduce($data) {
        $name = $data['name'];
        $profession = implode(", ", $data['profession']);
        $languages = implode(", ", $data['languages']);
        $frameworks = implode(", ", $data['frameworks']);

        $intro = sprintf("Hi, I'm %s, and I'm %s.\n", $name, $profession);
        $skills = sprintf("I am good at %s and enjoy working with %s.", $languages, $frameworks);

        return $intro . $skills;
    }
}

$data = [
    'name' => 'Damyan',
    'profession' => ["Full-Stack Web Developer", "UI/UX Designer"],
    'languages' => ["PHP", "JavaScript", "SQL"],
    'frameworks' => ["Laravel", "ReactJS", "AngularJS"]
];

echo Developer::introduce($data);
```

<div>
    <h2>Skills:<br><br>
      <p>
        <a href="https://github.com/isabella-projects">
          <img src="https://skillicons.dev/icons?i=html,css,sass,js,jquery,nodejs,react,angular,vue,php,laravel,ts,jest,vite,webpack,mysql,wordpress,xd&perline=6"/>
        </a>
      </p>
    </h2>
</div>


