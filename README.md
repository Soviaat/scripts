<h1 align="center"> Automatic World Backup script for OBS </h1>
<div align="center">
  
  [![Badge License]][License]  [![Badge PyVersion]][#] [![Badge OBS]][#]
      
</div>

The idea is simple. You select on which action should the script activate (On Stream Stop/On Recording Stop). When that action is triggered, the script basically takes the specified World files and parses them into a .zip archive, which then will be placed into a folder named after your world in the specified backups folder of your choice.

For the ones who say `"ew, it's written in python"` stfu, it's either python or lua.
> [!NOTE]
> Shout out to [@Sube22](https://github.com/Sube22) for contributing with his idea.</h6>

<!---------------------------------------------------------------------------->

[License]: LICENSE
[#]: #

<!---------------------------------[ Badges ]---------------------------------->

[Badge License]: https://img.shields.io/badge/License-MIT-ffb03b?style=plastic
[Badge PyVersion]: https://img.shields.io/badge/Python_Version-%E2%89%A5_3.11-white?style=plastic&logo=python&logoColor=white&labelColor=%233773a5&color=%23fece3c
[Badge OBS]: https://img.shields.io/badge/OBS_Version-v30.x-white?style=flat&logo=obsstudio&logoColor=%23cfd1ce&labelColor=%23302E31
