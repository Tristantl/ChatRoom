class AboutMe {
    public function __construct(
      private string $name, 
      private integer $age, 
      private string $location, 
      private string $occupation
      ) { }

    public function getName() {
        return $this->name;
    }

    public function getAge() {
        return $this->age;
    }

    public function getLocation() {
        return $this->location;
    }

    public function getOccupation() {
        return $this->occupation;
    }
}

$aboutMe = new AboutMe("Tristan", "Lille", "Project Manager");
