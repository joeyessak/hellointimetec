# Learn and Code :space_invader:
Welcome to my first Learn and Code Learn and Code repository

## What I Leared :scroll:
During the inital installation of the .net sdk I installed .net 6 since it was the most current stable release listed for download and the only imediate options to select were .net 6 or .net 7 from the microsofts .net sdk download page

I was unaware of the syntax change so once i relized this, in order to follow along with the instructions provided i searched to find access to a link to download the .net 5 sdk. Once I was able to find this and install this I now needed a way to reference that particual sdk and set this as my default .net sdk to use globally.

Here is where the Learning kicked in :mag:

:sparkles: Through the magic of google i found out i needed to create a golbal.json file to reference the particular SDK i desired to use and set this file inside the /source directory we created following the instructions provided :sparkles:


``` json
{
  "sdk": {
    "version": "5.0.408"
  }
}
```
Once this was done and set all balance was restored and everything was now back on track and working as expected and my TargetFramework was now pointing correctly to net5.0 

In retrospect I learned to pay attention to the fine details. Had I been more attentive to realizing my TargetFramework was net5.0 from the start I probably could have saved my self some time and found the .net 5.0 sdk from the begining 

#Welcome To Learn and Code :saxophone:



