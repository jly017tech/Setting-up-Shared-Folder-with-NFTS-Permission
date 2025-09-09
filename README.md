<h1>Setting up Shared Folder with NFTS Permission</h1>


<h2>Objectives: </h2>

<ul>
  <li>NFTS stands for New Technology File System permissions and it giving permissions for the comptuers and users to whichever files they allow to get access</li>
</ul>



<h2>Introduction</h2>
<p>In this lab, it's about accessing the share folder where different departments access and upload word documents, powerpoint, videos, pictures and other file types.</p>


<img width="767" height="612" alt="Screenshot from 2025-09-08 09-42-57" src="https://github.com/user-attachments/assets/930567c0-efca-4da5-8ad1-a4537e3b037d" />



<img width="888" height="589" alt="Screenshot from 2025-09-08 09-46-10" src="https://github.com/user-attachments/assets/f33f8f65-4039-4900-8620-426891f7d987" />


<h1>Setting up File Services</h1>

<p>I create a folder name Shared and put in C drive (C:\\). Then, I went to GPO manaagement Editor and create GPO object rule call MappedSharedDrive and I copied source path directory folder, \\DCHuskyTech\Shared\, in the gpo rule setting and apply to the Users under the Actiuve Directory: Users and Computers.</p>


