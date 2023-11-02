1) How to create a new UML diagram and add it to the wiki page

a) mv foo.uml input #The file extension name must be .uml
   git add foo.uml
   git commit -s -m "xxxxx"
   git push origin

b) Give some time for the github workflow to run.
   It will take 1min to generate the output of your UML diagram.

   The reason why it take so much time is because the workflow will
   create a local plantUML environment and generate the output from
   there. So the output picture won't go to the public plantUML
   server.

b) Go to Wiki page
   Click "New page"
   Write a ref to the output picture:
   [[/output/foo.png|alt=test]]

c) Save the wiki page and enjoy.

Note that you can click the picture and zoom it if the chart is huge.
