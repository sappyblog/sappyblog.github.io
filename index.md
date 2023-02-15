### Manually merge files downloaded from IDM:
To manually combine the parts downloaded by IDM I like to use this command in CMD:
>  for /l %i in (1,1,amount_of_files) do type name_for_parts%i >> name_of_output
<br>
. Replace amount_of_files with the amount of files you'd like to combine. <br>
. Replace name_for_parts with the name and extension of the files (without the number at the end). Don't remove the %i at the end! <br>
. Replace name_for_output with the name and extension of the file that gets created.


#### Example:
> for /l %i in (1,1,8) do type video.mkv%i >> video.mkv

#### Source: 
> https://superuser.com/questions/988213/how-to-manually-merge-files-downloaded-by-idm
