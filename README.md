namespace AboutMe
{
    public class Person
    {
        public string Name        { get; } = "Mathis";
        public string Location    { get; } = "France";
        public int    CodingSince { get; } = 2024;

        public List<string> Languages { get; } = new() { "C#", "Python", "TypeScript" };

        public List<string> CurrentlyCreateMod { get; } = new()
        {
            "Embedded Systems", "Low-level C"
        };

        public string Goal { get; } = "Share my modding tools";
    }
}
