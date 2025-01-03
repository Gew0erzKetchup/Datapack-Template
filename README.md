# Datapack Template

## Instructions

1. **Download and Extract the Files**  
   Download the files and extract them to your desired directory.

2. **Edit the `pack.mcmeta` File**  
   Open the `pack.mcmeta` file and modify both the description and the `pack_format` value.  
   Example: For version 1.21, the `pack_format` value should be 48. You can find the correct `pack_format` for your Minecraft version here:

   [Minecraft Wiki - Data Packs](https://minecraft.wiki/w/Data_pack#Pack_format)
   or here:

   | Minecraft version | `pack_format` |
   |-------------------|---------------|
   | 1.13 - 1.14.4     | 4             |
   | 1.15 - 1.16.1     | 5             |
   | 1.16.2 - 1.16.5   | 6             |
   | 1.17 - 1.17.1     | 7             |
   | 1.18 - 1.18.1     | 8             |
   | 1.18.2            | 9             |
   | 1.19 - 1.19.3     | 10            |
   | 1.19.4            | 12            |
   | 1.20 - 1.20.1     | 15            |
   | 1.20.2            | 18            |
   | 1.20.3 - 1.20.4   | 26            |
   | 1.20.5 - 1.20.6   | 41            |
   | 1.21 - 1.21.1	  | 48            |
   | 1.21.2 - 1.12.3   | 57            |
   | 1.21.4 ​[upcoming] | 61            |


4. **Update the `load.json` and `tick.json` Files**  
   Navigate to `minecraft/tags/functions/load.json` and edit the example to suit your needs.  
   Do the same for `tick.json`.  
   **Important**: The content in both `tick.json` and `load.json` must be identical.

5. **Apply Changes in the `data` Folder**  
   Go to the `data` folder and ensure that the examples match the changes you made in `load.json` and `tick.json`.

6. **Enjoy!**  
   Your datapack is now ready to use. Enjoy!

## Links

- [Minecraft Wiki - Data Packs](https://minecraft.wiki/w/Data_pack#Pack_format)
