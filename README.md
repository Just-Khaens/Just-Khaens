```c# console
Console.Title = "About Me";
Console.ForegroundColor = ConsoleColor.White;

def aboutMe {
	Console.WriteLine("Hello World!");

	string profession = "game developer and a student"
	Console.WriteLine("\nI'm a " + profession + ". I'm currently learning C# for Unity!");
	
	int age = 14

	if (age =< 18) {
		Console.WriteLine("I'm a broke teenage guy in high school leading a studio of 9 other friends.");
	}

	else {
		// Exit the program after input
		Console.ReadKey();
	}

	Console.Write("These are some of my favorite things: ");
	string[] favorites = {"Indie Rock Music, ", "Slice Of Life Anime, ", "Minecraft, ", "Rhythm Games, " , "and WW2 Games."};

	for (int i = 0; i < favorites.Length; i++) {
		Console.Write( favorites[i] );
	}

	Console.WriteLine("That's all about me, thanks.");
	Console.ReadKey();

}
