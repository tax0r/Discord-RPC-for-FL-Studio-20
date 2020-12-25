# Discord RPC for FL Studio 20
This C# program allows you to set your current FL Studio 20 project as your Discord Rich Presence status. How cool! 

__NOTE__: I only tested the Program with FL Studio 20 and it will probably throw an exception while used with an older / newer version of FL.

* **How to compile the Source Code**
- Run the .sln file.
- Navigate into 'Program.cs' and open the 'clientInitialize' method.
- Paste your clientID into where it says 'MY ID',
- Compile the program.

* **HOW TO INSTALL (with autostart)**
- Download the current release.
- Press WIN + R and paste "shell:startup" into the prompt.
- Copy the .exe into the folder or copy a shortcut to the .exe into it.
- Execute the .exe or restart your PC and enjoy.

* **HOW TO INSTALL (without autostart)**
- Download the current release.
- Place the .exe somewhere you will __find it again__.
- Execute the .exe and enjoy.

* **Final words**
The Code is messy and a bit weird, but 99% by **me**. Thanks to [Lachee](https://github.com/Lachee) for providing the [RPC Wrapper](https://github.com/Lachee/discord-rpc-csharp) for C# and thanks to [Discord](https://discord.com/) for providing the RPC in the first place.
