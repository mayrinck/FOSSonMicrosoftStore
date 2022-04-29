# Free and Open-Source Software Repository on Microsoft Store

![banner](https://user-images.githubusercontent.com/21313332/124395717-fae21080-dcdb-11eb-8185-7470b2ee552f.png)

As we all know, one of the main problems with Microsoft Store is their lack of a self-maintained software repository, where they would verify and upload new versions of certain apps regularly, pretty much how the things are with every linux distribution. Also, the extensive burocracy when it comes to publishing and app makes open-source projects a lot more far from this platform. I hope Windows 11 change that, but for Windows 10 and prior, things may remain the same.

So, thinking of that, I decided to convert my MS Developer account into a "Free and Open-Source Software Repository", where we can upload and keep updated some of the open-source apps we think that deserve to be there the same way they are displayed on their official sources... No "Gimp PRO" or stuff like that, just the vanilla software, properly credited and with all licenses, privacy policy and other information directly related to the original developers.


# How does the software is converted? Is it safe?

The process uses the MSIX Packaging Tool, which is available on Microsoft Store too, It does a 100% unmodified and safe conversion of the software from the installer to become a Microsoft Store compatible package. Every converted software is downloaded from the most secure link available from the creators, ensuring the safety of every application. Also, patch notes and other stuff come from the same source.

Bugs and other issues shouldn't be pointed here, as the conversion don't mess with the source code of the original software. If you have any issues with a software available here, we strongly recommend that you go to the developer's website and try to get some help there.


# How to contribute:

You can contribute by alerting about updates of the apps, as well as translations and recommending new softwares to be added to the repository. Check out the instructions below to make sure you will do everything correctly:

1. Only suggest softwares that are working on Windows 10 without any tweaks and are not already available on the store through official developer accounts.

2. The software must be sent as a TOPIC on the discussions, under the **[Requests](https://github.com/mayrinck/FOSSonMicrosoftStore/discussions/categories/requests)** Label and Discussion Topic. You must point every details that are requested in the fixed topic.

3. You can also send a pull-request to add translations and other useful information for any software that is already available.

4. There are some [guidelines](https://docs.microsoft.com/en-us/windows/uwp/publish/store-policies) to upload softwares to Microsoft Store. At this point, browsers and emulators are not allowed. Further instructions are also inside the link.

5. We will remove any software from the store as soon as a software is sent to the Microsoft Store from the original developer's account OR by request of the developer.


# Softwares being maintained at the moment:

<sub>
  <sup>
    - <b>Under Evaluation</b>: Means that we are looking for the info's needed to upload and convert an app, as well as checking if it's not already available on Microsoft Store.
    <br>
    - <b>Under Conversion</b>: Means we are converting the software to the MS Store format and creating the artworks needed for the package to look good on the store.
    <br>
    - <b>Under Certification</b>: Means the software was uploaded and it's page is also set-up, but Microsoft is verifying if everything is really ok with the app and the information we gave them.
    <br>
    - <b>Package Broken</b>: Means the software was uploaded but did not pass Microsoft's testing steps. Might require further investigation.
    <br>
    - <b>Can't be Converted</b>: Means the software cannot be converted without causing critical problems.
  </sup>
</sub>
<br>

| Software Name         | Maintained Version | Architecture  | Status / Download |
| --------------------- | ------------------ | ------------- | ---------------- |
| Antimicro             | **2.23**           | x64           | [Download](https://www.microsoft.com/store/apps/9n1fcfq6p5lw) |
| Avidemux              | **2.7.9**          | N/A           | ***Can't be Converted*** |
| Cinelerra             | *N/A*              | N/A           | ***Installer not found*** |
| DIA - Diagram Editor  | **0.97.2**         | x64           | [Download](https://www.microsoft.com/store/apps/9npvgp9l96jj) |
| Gedit                 | **3.20.1**         | x64           | ***Can't be Converted*** |
| GIMP                  | **2.10.24**        | x64           | ***Can't be Converted*** |
| HandBrake             | **1.4.0**          | x64           | *Under Evaluation* |
| LibreOffice           | *Soon*             | x64           | *Under Evaluation* |
| OpenOffice            | *Soon*             | ---           | *Under Evaluation* |
| OpenShot Video Editor | **2.5.1**          | N/A           | ***Can't be Converted*** |
| Super Tux Kart        | **1.3**            | x64           | *Under Certification* |


# Open-Source Softwares officially posted/supported by developers:

| Software Name         | Active? | Store Page       |
| --------------------- | ------- | ---------------- |
| Audacity              | Yes     | [Official Download](https://apps.microsoft.com/store/detail/audacity/XP8K0J757HHRDW) |
| Blender               | Yes     | [Official Download](https://www.microsoft.com/store/apps/9pp3c07gtvrh) |
| Gedit                 | No      | [Official Page](https://www.microsoft.com/store/apps/9pl1j21xf0pt) |
| Inkscape              | Yes     | [Official Download](https://www.microsoft.com/store/apps/9pd9bhglfc7h) |
| Kate                  | Yes     | [Official Download](https://www.microsoft.com/store/apps/9nwmw7bb59hw) |
| KDE Connect           | Yes     | [Official Download](https://www.microsoft.com/store/apps/9n93mrmsxbf0) |
| Krita                 | Yes     | [Official Download](https://www.microsoft.com/store/apps/9n6x57zgrw96) |
| Kdenlive              | Soon    | Soon |
| Mozilla Firefox       | Soon    | [Official Page](https://www.microsoft.com/store/apps/9nzvdkpmr9rd) |
| Notepads              | Yes     | [Official Download](https://www.microsoft.com/store/apps/9nhl4nsc67wm) |
| Shotcut               | Yes     | [Official Download](https://www.microsoft.com/store/apps/9PLNFFL3P6LR) |
| VLC Media Player      | Yes     | [Official Download](https://www.microsoft.com/store/apps/9nblggh4vvnh) |
