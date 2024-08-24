# cad-frc
bad frc cadding (v2)

# session 1:
i've been putting off doing frc cadding, but here i am again.
ok, so i wanna do 2024 this time.
also, i learned about some new design techniques during the time that i did my previous frc cad, and between this session and the last frc cad session
the first one is called master sketching
i'm still not entirely sure on how it works/what you're meant to do, but you basically plan out the location of pulleys motors and moving stuff, before deciding on the shape of the plate. 
https://www.frcdesign.org/best-practices/mastersketch-setup/
ok i was wrong, maybe it isn't the motor  location, i guess that can change and stuff. 
the other one is called parametric designing
i don't know how to explain it, but an experienced cadder in the team told me that it's like making your part studio look like your assembly. i kinda liked the idea because then i wouldn't have to fasten 10000 things again.
https://www.youtube.com/live/1v7lYKwmTyM
https://www.chiefdelphi.com/t/full-robot-design-thought-process-workflow/443307
this is made by a guy called david, who also made frcdesign.org
i wasn't sure how you were meant to get bearings and pulleys in, until i looked through my featurescripts and found
"in-place bearings" and
"belt and pulley gen"
but i don't think i can generate motors, which is fine.
i'm just going to fuse a bunch of robots again, but also try to understand why they did a thing that they did.
(aka how their robot systems work and stuff.)
ok so
254 hadn't yet released their tech binder :(
althoughhhh
1678 has released their cad (only their cad) and a strategy document
![image](https://github.com/user-attachments/assets/3ebc9850-b126-4722-8d00-3affa642e8c6)
uhhhhhhhhhhhh so i forgot the key words.
erm
what were they again ???
![image](https://github.com/user-attachments/assets/92934e88-b608-4816-be69-9a01da2d3737)
ah right, a build thread.
finding "open alliance" has 612341824 trillion different build threads
https://www.chiefdelphi.com/tag/openalliance
i'm just gonna drop the build thread links here.
https://www.chiefdelphi.com/t/wildstang-robotics-program-team-111-and-112-build-blog-2024/446622
by 111 and 112 (111's sister team)
https://www.chiefdelphi.com/t/frc-4322-clockwork-2024-build-thread-open-alliance/447076
by 4322
https://www.chiefdelphi.com/t/frc-4481-team-rembrandts-2024-build-thread-open-alliance/441907
by 4481
https://www.chiefdelphi.com/t/frc-95-the-grasshoppers-2024-build-thread/442176
by 95
https://www.chiefdelphi.com/t/team-177-bobcat-robotics-2024-build-blog/447633
by 177
https://www.chiefdelphi.com/t/frc-6328-mechanical-advantage-2024-build-thread/442736
and by 6328
there's a lot more to go through, so uh... time to scroll i guess
![image](https://github.com/user-attachments/assets/1e90862e-811c-4e5e-8b1e-a06c3d91b9b3)
where onshape link :( it's after kickoff :(
me watching the 4 onshape tabs eat all of my ram
![image](https://github.com/user-attachments/assets/2a91ebc8-0be0-4742-8f9a-862b45841487)
ok, so 111 uses an under the bumper intake
![image](https://github.com/user-attachments/assets/e950ab89-32ea-4f71-982b-3b4ca906a542)
that goes into an adjustable angle shooter.
they also have a climber.
![image](https://github.com/user-attachments/assets/dd3e4c0c-e530-41ad-85e2-0ca49fefe146)
they also use a crank or a linkage or something to move the adjustable angle shooter up and down which is quite interesting.
![image](https://github.com/user-attachments/assets/0febce07-b779-47dd-ab24-a10525fb3cd0)
dude i have no idea what's going on here.
i...
all i can see is an adjustable angle shooter
it just loooks like a mess of wheels and rollers elsewhere. i assume it's meant to be an intake.
![image](https://github.com/user-attachments/assets/e2e43890-5575-42a0-adf6-59537abfbd78)
thisi makes much more sense, i was able to move the intake out.
ok, so the intake moves up and down using a sprocket and some chain, they have a climber.
![image](https://github.com/user-attachments/assets/40057577-87e2-4217-8ea7-1c8761d82152)
they make their shooter adjust angles by using a moving gear and a stationary gear. 
![image](https://github.com/user-attachments/assets/079c3e99-4c9a-4bb5-adb2-0c04b92b167b)
and their shooting is one sided?
i don't understand why
it's probably some mathematical concept that i don't know of (aka all of them)

# session 2:
i'm kinda hungry
(it's 6 am and i didn't eat much last night)
![image](https://github.com/user-attachments/assets/88c71c92-3f4b-4b00-9e77-d854fd863178)
ok, so this is their intake.
![image](https://github.com/user-attachments/assets/8b8c3751-acc8-4cc9-bc7a-2738884a51fe)
and it moves back to  here-ish.
![image](https://github.com/user-attachments/assets/f19032e5-8bc4-4c89-9516-4ed85d8622a4)
they use  a stationary gear and a smaller gear to move it.
they seem to not have gone for a climber, but they have an adjustable angle shooter.
![image](https://github.com/user-attachments/assets/77383ef4-296c-472b-b2ff-0262a2e0734b)
ok, so i'm not sure if it actually is adjustable. i see nothing that can make it move, even though i can move it in the assembly which usually means that they want it to move in real life.
after looking around for like 5 minuutes straight, i can't find anything that makes it move.
![image](https://github.com/user-attachments/assets/73870fd0-fe89-4d5f-981c-1db138c53924)
6328 has an under the bmper intake, and has modified their bumper to let the note fit through.
![image](https://github.com/user-attachments/assets/b903de6b-8bae-4c6a-a86c-1698a7e0c018)
i can see an adjustable angle shooter, and a mechanism to do the amp (i forgot amp exists)
uh yea that's about it.
ok, so selection times
i think i might want to try and go with an adjustable angle shooter and some way to do amp, although i've seen teams with adjustable angle shooters just roll up to the amp, adjust the angle of their shooter to be nearly parallel with the amp slot and use a little bit of power to get the note in. 
https://youtu.be/AaAfX_DwbJ0?t=22
here's a video to explain it.
![image](https://github.com/user-attachments/assets/8b4a1c5f-9f93-402a-95ff-d13c54e3709b)
i was reading through frc design, and i found this.
well ok. i mean that's fair.
i think i'll also do an intake that moves in and out of the robot
and maybe a climber if i can fit it in.
i would also like to sort of make a checklist of things that i need to do (make plates etc) to help me remember what i need, since i forgot to make a bunch of things in theh previous frc cad, and that lead to me having to go back and redo a bunch of things, and make shafts and stuff, etc.
also, i just realised, that david (the guy who made frcdesign) only took like 6 hours to make a full robot, but took me like 60-70 hours. damn. skill difference is crazy.
ok, so the bad thing is, i don't necessarily know every single minute thing that i need to put into the checklist.
so uhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh
hmmmmmmmmmmm.
might as well not make a checklist
or
idk
eh i won't
![image](https://github.com/user-attachments/assets/4ef4064a-ef4b-4e88-a3c6-74456f760bc9)
i started off with this drivebase.
i'm going to read through frc design best practices real quick, and then start doing stuff
i'll refer back to it to check on some things and best practices

# session 3:
hmmmmmmmmmmmmmmm
ok so i probably should've made the checklist, so i know where to start, but uh...
hmmm
honestly
idk
![image](https://github.com/user-attachments/assets/d91778b9-833e-4fb5-994c-4091e144f71a)
i named 2 folders for now. 
i'm just kinda stuck on where to go right now.
i guess i might make a note intake ?
idk dude.
ok well apparently you're meant to put them in separate documents, but that doesn't matter. 
oh and i thought that you're meant to make a master sketch for each subsystem, but you're meant to make one for the entire robot. 
also i don't need the context of the drivebase for mastersketches, so that's cool i guess. 
![image](https://github.com/user-attachments/assets/72f3fd22-3e32-4f38-ba9b-ac3eefc05176)
i started out by sketching the drivebase. 
hmmmmm.
i decided to grab the dimensions of a note. 
they're 2 inches thick.
![image](https://github.com/user-attachments/assets/04ce7190-aa6f-45ef-93b2-acb9d2e135ba)
1678 uses something on the side to i think guide the note in. also, it seems like you are able to intake the note pretty steeply, so that's interesting.
i could also either use a roller, or wheels
i think i'll use rollers, since they can cover a larger area.
![image](https://github.com/user-attachments/assets/340e79a2-c4d5-4dcc-b3a1-a4a9afe9fcd7)
i'm  having trouble manuvering the "note" between the rollers, and it keeps on being horizontal. i used transform and selected one line to try and move them all, but i had to select all of the lines.
![image](https://github.com/user-attachments/assets/bb8c4fd4-eabe-4eb4-aef9-214ffc15a441)
this... might work?
![image](https://github.com/user-attachments/assets/5416d951-3ea8-4eda-908f-82bc7651bdd8)
i decided to use a 2 inch by 2 inch cube to sort of map out where it can go, because moving the rectangles can feel clunky and takes a long time, although i cna just have a lot of rectangles, which could be effective.
i think ima use a bunch of rectangles, i feel like the master sketch isn't meant to look like this, but now it will. 
actually, i think i want to check up on frc design to look at mastersketching again, since the main goal is to learn more abuot frc cadding, and how to be better.
![image](https://github.com/user-attachments/assets/77435092-46d4-4041-9fb8-cfd9ae8492b9)
hmmmm ok
![image](https://github.com/user-attachments/assets/804e1e84-a700-46c8-9d75-55016a678d41)
wait a minute... i was right. 
hmmmm ok. 
i'd been doing the master sketch not in any folder, so i guess i'll move this into the intake folder, and build off of there. 
now, i need to show the extension limits, now i'm not sure if it means how far something extends in the robot (e.g. intake or adjustable angle shooter) or if it means frame perimeter. 
![image](https://github.com/user-attachments/assets/778ee09f-9fee-4a93-94a2-69f155792d9c)
ok, so this is an image from frc design, and i can sort of see a rectangle around the robot which tells me that it's probably frame perimeter. 
