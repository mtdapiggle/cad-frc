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

# session 4: 
welp i guess i gotta look up the game manual. 
![image](https://github.com/user-attachments/assets/578d160a-e90b-4689-8292-5b64cdcff00c)
hmmmmmmmm ok.
![image](https://github.com/user-attachments/assets/2292af84-5390-46cc-8a02-2e01a4e54429)
considering the general size of a swerve drivebase is around 650 mm, this is quite big. 
though i guess that's the reason why the unqualified quokka's robot can extend out that far
(btw this is the unqualified quokka's robot):
https://www.youtube.com/watch?v=FURTxVVXUfM
a robot in 3 days is basically like a thing where people gather together to build a robot within 3 days of the kickoff, usually attempting to be able to do all of the different things in the game (i think) it's usually not a full frc team that does it. there's also other robot in 3 days groups, like cranberry alarm. i'm pretty sure unqualified quokkas is the first australian ri3d group/team. 
they combined an intake, an amper and a shooter all into one arm, which kinda astonishes me, since i would've personally went for like a different subsystem for every single one. 
![image](https://github.com/user-attachments/assets/58380890-79ca-4e80-8da5-1b4908c4abb0)
hmmmmmm, i might have a problem with the note hitting the bumper, but it should be fine right. right???
![image](https://github.com/user-attachments/assets/5e920a10-b0c7-4088-89d8-8f50c41d2258)
i think this could work. 
![image](https://github.com/user-attachments/assets/6743e824-d5c1-4ae8-bcd8-3992e68aec3b)
i feel like this is a bit short/small for some reason.
oh ok nvm i think i know the reason, it's because you usually add the radius of the pool noodle. 
![image](https://github.com/user-attachments/assets/e42e20aa-5763-4234-ae1c-ad940e723e4a)
yep that looks more like it. 
![image](https://github.com/user-attachments/assets/a099c656-7ab0-4d3a-a09f-08fbeabe52ed)
i could make a roller to the top right of the lowest roller.
![image](https://github.com/user-attachments/assets/7bef6d02-9ef2-47d7-b6b8-f1510f66ffc2)
1678 uses 2 rollers, with both of them being smaller. i might do that. 
![image](https://github.com/user-attachments/assets/0194572d-a1e1-43ad-879d-c74842a88871)
i think this mighttttt be good? idk.
ok, time for other intake stuff.
like
like
pivoting.
i've seen a couple things that pivot, and they all use sprockets and chain/nearly all the time/most of the time/yeah.
e.g. the unqualified quokkas entire shooting, intaking and amping is on a pivoting arm. 
so i think that when you need a more accurate pivot/spin, you'd want a higher gear ratio, so you can control it more precisely. 
![image](https://github.com/user-attachments/assets/c5db12a4-6f0e-4a60-9140-86737987cfe6)
i found this intake calculator on recalc, but i dodn't think i'll need it. 
![image](https://github.com/user-attachments/assets/4fb80bdd-bdeb-4119-a813-e3a22a50ea19)
oooooooo a flywheel calculator, i likely won't need that though, since unlike other games, you can only store one game piece at a time.
![image](https://github.com/user-attachments/assets/2e613b71-1214-459c-9eb4-c78ccbbe30b7)
now this is what i need.
![image](https://github.com/user-attachments/assets/a8e06b0d-42ff-4a02-92c9-39a5f0ad03eb)
uh what's this. 
ok, so i found out that increasing the size of the chain increases the pitch and the size, but not always.
![image](https://github.com/user-attachments/assets/2be0b4f4-d6b2-4319-b4f6-227331dfaf51)
uhhhhh which one is it. 
ok so it's single strandd, which makes sense
![image](https://github.com/user-attachments/assets/c7fa4dd8-a593-4484-8a87-79ae3e7ad698)
the ddifference between #40 and #41 is crazy.

# session 5:
![image](https://github.com/user-attachments/assets/41bc44e9-96a4-4fe8-9eed-a491fc6867af)
i think i'll use #35, since it's strong and has a good tensile strength, there also is no #40 cots (commercial off the shelf) sprockets, so that's cool. 
ok, so i'm going to figure out a gear ratio.
i think that something around 10:1 would be good, or maybe even higher, something like 20:1 at maximum. 
now i could use versaplanetary gearboxes to do this, but the motors that are compatible with the versaplanetary gearboxes aren't extraordinarily strong, and we have to move an intake/shooter, so i don't think i should use versaplanetary gearboxes. 
hmmmmmmmmmm
i think i should use gears and sprockets, i think they might be safer. 
![image](https://github.com/user-attachments/assets/5d7a5688-8ea5-4343-8079-5070f5dc20af)
1678 uses a double gear setup, which i assume is to make sure that nothing slips and things don't go badly, which is fair, or it could be to lower the stress on the gears, since there would've been more stress on one gear, when it could've been displaced over 2 gears.
now that i think of it, this could've been the stuff that i planned out. anyways. 
i decided to look at frc design again, just to check how i should setup the part studios. 
![image](https://github.com/user-attachments/assets/821038a5-e055-4478-a031-7f194873b816)
ok wait, i just realised that i misunderstood this, i thought it meant one master sketch per subsystem, but each master sketch are in different part studios, but now i realised that they mean that a different sketch just meaning a different sketch in a singular part studio.
ahhhhhhh well, time to pull the mastersketch back out. 
argh ok. 
![image](https://github.com/user-attachments/assets/d57f9e65-95e1-4050-bf2d-ad4d9f1d485b)
i started to make the other master sketches. 
![image](https://github.com/user-attachments/assets/56a6f0af-c416-447e-9024-1d0b15175126)
things just feel larger in the part studio. 
![image](https://github.com/user-attachments/assets/e0646296-35d4-4d50-9959-2bec3cbac886)
![image](https://github.com/user-attachments/assets/b8a94944-8bb6-44a5-b622-387aba895a4e)
things... just aren't adding up.
![image](https://github.com/user-attachments/assets/ef4f04f2-1752-482c-9f8b-ccde4af98f71)
uh huh...
![image](https://github.com/user-attachments/assets/94e5bc54-4d69-47f1-a7ad-e07ca8d70cf3)
i love it when onshape omits the 0.4 mm when calculating inches and singlehandedley stuffs everything up. 
or maybe it doesn't
idk.
ok wait nevermind i'm such a dumbass, i am so dumb (i thought my measurement was 205 cm, and read the actual one normally, as 211 cm, which is why i thought something is wrong.)
but the wacky speaker opening problem is still a thing.

# session 6:
![image](https://github.com/user-attachments/assets/7d1acd6a-dcd4-4793-bcfb-51ebe9bb639c)
this all makes no sense...
why...
honestly i think i'll just move on, it's not worth wasting time on this.
![image](https://github.com/user-attachments/assets/7825b9e1-9026-46ea-89fb-7dd88af167c2)
i have no idea what a serialiser is, so uhhhhh. 
hmmmmmmmmmmmmmmmm.
i searched up for serialisers and it didn't come up with anything useful for the most part, but i think i got the general idea of what a serialiser is, i think that it's a subsystem/thingy that usually is between the intake and the shooty thing, that basically takes the game piece from the intake to the shooter? idk.
i think that kinda makes sense to me now. 
hummmmm...
ok, so i have to get the note from the intake to a possible shooter position, now i wonder if i want to go beneath the stage.
i think it would be nice.
hmmmmmmm i also have to sketch out the possible positions of the intake/shooter
surely it's fine !
o wait i forgot to do the amp in the master sketch
that's not good. 
![image](https://github.com/user-attachments/assets/d42632da-91cd-498b-a08b-c96eb80afd69)
hmmmmm quite interesting.
![image](https://github.com/user-attachments/assets/f1b82c46-22c6-47ae-afaf-c9beb36c30e1)
i think i might actually put the extension limit and the notes into a separate sketch.
![image](https://github.com/user-attachments/assets/5b14b02f-d112-4cad-940d-0f0a513a25eb)
it has been moved.
ok, so a small problem, i just realised that by putting the notes in a sketch before the intake, i can't see where i should put intake stuff, which isn't good. 
hhhhhhhhhhhhmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm
![image](https://github.com/user-attachments/assets/f4fcb408-3d03-4910-9ce3-c555f1cf8449)
the roller army approaches.
![image](https://github.com/user-attachments/assets/ae6d7d44-b91f-4d63-9426-d55de9982102)
ok, so i can make the rollers go downwards, and then have the entire robot be generally lower, which i think could be good, or i could have it higher.
hmmmmm i think i'll have it lower. 

# session 7:
![image](https://github.com/user-attachments/assets/2a804c1f-7c64-481e-8101-64791a7cd92f)
me think.
actually, i'm not sure if i should make it go downwards, necause if it does, it'd have to go at a steep angle into the shooter, which i don't think is good.
i was looking at 1678's cad for guidance, and wondered why they had a couple of rollers up really high, i thought that it could be for amp since that's like the only target up high, so i did some digging.
https://youtu.be/_EfZcbMWMVY?t=65
i looked at their gameplay footage and saw that it is indeed for amp. 
quite interesting amp mechanism. 
hmmmmmmmmmmmm ok so
i think i might just keep it flat. 
actually, i probably should sketch out my shooter before trying to make the indexer/serialiser, so i know where everything is before making it. 
![image](https://github.com/user-attachments/assets/0deef2e0-7c04-4b77-82f0-5a2325c715e0)
i'm starting to see why master sketches can be good. 
![image](https://github.com/user-attachments/assets/b1fd48d0-34da-4a26-9e28-9bea3c09ccca)
i feel like the shooter should be around? the middle of the drivebase. 
![image](https://github.com/user-attachments/assets/00d80188-3f67-41df-939f-4be81b88a0f9)
so around 60 degrees at maximum, and around 0 ish degrees 
i might have to place the shooter a bit higher so i can get it at 0 degrees.
![image](https://github.com/user-attachments/assets/fbf0b8e1-6885-407e-a92f-b1df1db11b80)
this might be where i place the pivot for the shooter. 
![image](https://github.com/user-attachments/assets/83687bef-b01f-4ce3-a1ee-cef94c740f78)
i think that i'll use 2 pairs of wheels to shoot the note, now i'm not sure why 1678 put their wheels on one side, i think i'll look at other examples to see why/find out. 
i looked at 6328 and they have 2 pairs of wheels on both sides, so i might also do that. 
hmmmmmmmmmmmmmmmm ok.
i think i might use 3 inch or 4 inch wheels, i don't think it matters too much in this game, considering that you only shoot one game piece at a time, so..
hmmmmmmmmmmm
me think. 
![image](https://github.com/user-attachments/assets/2b6b8f7b-ed47-4580-b1ae-27788f589dd7)
i think this might be good. it's only a master sketch anyways.
![image](https://github.com/user-attachments/assets/39c0e9c9-8059-4440-bf92-de1029f031c1)
i kinda realised that i probbbably should make the shooter higher up. 
me thinking. 
![image](https://github.com/user-attachments/assets/46ef9503-6772-487a-aa70-a83e608b7454)
i think i've figured it out? i don't know dude. 
comparing my master sketch to the one on frc design, there's a lot mroe on the frc design master skettch. idk what i'm doing wrong.
![image](https://github.com/user-attachments/assets/7654bc58-58a6-4833-881b-44d2becf5443)
i think i might have to sketch out where the possible locations of things are meant to go. 

# session 8:
![image](https://github.com/user-attachments/assets/b529115c-2969-491a-afec-50561bebaa85)
i'm not sure how i'm meant to know where it's meant to stow, (i can give a rough area, but it's not going to be like extremely accurate/down to the mm) so i think i might use a circular pattern so that it can be accurate. 
![image](https://github.com/user-attachments/assets/72f0acd6-0e81-4eda-81b7-8cd5828856c8)
yeah i think this could work.
now i need to make the positions of the shooter.
![image](https://github.com/user-attachments/assets/bb2aa52d-f156-421e-81b2-089c7b3723dc)
hmmmmmmm
ok, i think i should start trying to make stuff now.
uh so yea.
![image](https://github.com/user-attachments/assets/fae15c85-a0ee-48cd-85f5-293fd92eb1c2)
hmmmmmm...
uhm
my bad. 
![image](https://github.com/user-attachments/assets/9feeb672-bf76-4c0b-baad-6d46ba6480c7)
it has been derived. 
i think i might want to structure my stuff better. 
![image](https://github.com/user-attachments/assets/4615bd3c-450a-4fad-b49a-768d060475bf)
progress is good, but i gotta figure out the shape of the plate that i want, and where i want the intake to pivot from. 
the intake also hits the bumpers, which isn't good. 
![image](https://github.com/user-attachments/assets/595c1154-e856-4646-8054-c0f2e4f40361)
ayeeeee progress !
![image](https://github.com/user-attachments/assets/a6bde715-3eee-4253-80c7-7af75b6d09f6)
as i start to create the intake arm, i realised something very bad. the circular pattern is too close to the bumper
asdjflkasdjfa;ksfda;sfd;kdsjfkladsf
![image](https://github.com/user-attachments/assets/13157357-35fb-4b4a-a439-f9469fcb1ccd)
surely this is enough. surely. 
ok, so right now i'm thinking of putting a sprocket on the inside of the drivebase, and then like 1678, mount the intake on the outside (between the drivebase and the bumper), i think that they mounted the intake on the outside because if they didn't, it'd hit the swerve modules, and that's not good. 
![image](https://github.com/user-attachments/assets/982358da-a07d-4ee3-adae-4d52797d39e7)
sooooo i looked at 1678's intake, and uhhhhh. they have it right up against the  bumper. i meannnn i coudld do that, but uhhhhhhhhhh.
hmmmmmmmmmmmmmmmmmmmmmmm
honestly i don't care, they can do what they do and they know what to do, whereas i don't know what i do what i'm meant to do and i'm doing what i'm doing.
i don't know what i just wrote, but
yeah anyways.
![image](https://github.com/user-attachments/assets/8246f2dc-8fc1-40a1-9579-ef4ea3d5cfee)
W tangent constraint moment. 
![image](https://github.com/user-attachments/assets/59427115-a87d-44eb-9322-915d1fd79d72)
dude...
what.
![image](https://github.com/user-attachments/assets/2622ffa1-beae-40f5-9c2c-35db93b927af)
why this no worky :(
![image](https://github.com/user-attachments/assets/e1cf453f-661a-4519-9cbe-432f416288ab)
WHAT MYSTICAL CONSTRANITS ARE HOLDING THIS
![image](https://github.com/user-attachments/assets/5cee3c5f-e795-4ce5-9878-df0fd361a010)
THESE ARE ALL THE CONSTRAINTS
![image](https://github.com/user-attachments/assets/c8dea7ba-1308-44e2-aef2-8114885bbb41)
if i move the right point, this happens...

# session 9:
bit of a gap between writing the commits n stuff, i apologise for it. (in hindsight i probably should've just exported the .stl file after i finished and then talked about stuff i did later, now i'm forced to sift through version history to find the exact time)
okie dokie writing time.
![image](https://github.com/user-attachments/assets/a83b8ab9-68e5-44a6-8a74-954eca1c9318)
i fixed this problem by using a normal circle instead of using a 3 point arc and then trying to make it tangent. i also had to put things into place and make sure things don't go wrong. 
now, i needed to somehow figure out a way to mount stuff like the sprocket, i checked the WCP store, and realised that the sprockets have holes in them so that you can mount them to plates with bolts, now i just needed a way to mount the intake to something. 
ok, so after a bit of thinking, i had decided on mounting the sprocket onto the inside of the drivebase, and then use bearing blocks to hold bearings, and then mount the plate outside of the drivebase, and spacing the bumper out somehow (ya)
i also needed to decide on gear ratios. i eventually decided on a 20:1 gear ratio, since i think it's better to be precise and have enough torque to lift the intake up and down. 
i think i will go with a 12 tooth pinion to a 60 tooth gear, and then a 15 tooth sprocket into a 60 tooth sprocket, making it 20:1. 
![image](https://github.com/user-attachments/assets/d475609f-491a-453a-9bc9-0a82f875d41b)
and then i realised that the currnet setup can't really facilitate using a 60 tooth sprocket, as it will likely hit the swerve modules (aka bad)
hmmmmmmm
i think i'm foced to downgade here, and i don't think i'm really able to up the gear count, sooooo.
![image](https://github.com/user-attachments/assets/7d9f81af-d153-448b-9f53-488b4181dae2)
oh... oh no...
i think i might have to do something like 1678, and i can now understand why they mounted it the way that they did.
![image](https://github.com/user-attachments/assets/e515c292-4d16-4d2e-862c-8c5c97b0d5d6)
cool ok. 
![image](https://github.com/user-attachments/assets/6b50e56f-b934-4021-b1e5-1cc10ee7bbb2)
hmmm that's a bit close.
![image](https://github.com/user-attachments/assets/7506ded4-dcb0-402e-8d13-738d79ff82cc)
awwwww no dude...
![image](https://github.com/user-attachments/assets/4fbc0aff-4bd2-4e8d-b5fd-984e602d96c2)
uh what.
![image](https://github.com/user-attachments/assets/897623b5-89d5-4e49-8ae7-87efb2ccbca3)
mmmm nvm i don't think i need 12 holes.
![image](https://github.com/user-attachments/assets/94e9413a-9831-4614-9b88-efbbd2588e84)
hmmmmmmm, 1678's intake mounting is quite interesting, they have 2 plates, and one connects to the intake? why couldn't they just have one plate?
there's obviously a reason behind it, but i'm not sure why...
my small cad brain doesn't understand. 
it's probably a problem that i would have to face in the future (aka me right now, writing this), so i think i should solve it and understand it now, before moving on, and it'd help me to understand more design problems and how to solve em, so i guess i should try and solve it. 
okay, so...
![image](https://github.com/user-attachments/assets/cd0373d7-39ea-425d-ba5b-a2b887535bb1)
from what i could see, that's a bearing hole that holds the shaft and a bearing, which allows the plate to spinnn.
so i think i figured out why they needed it, they needed it because they wanted to min max the space that they can pick up the game piece from (i think, i see no other reason)
well ok. 
i don't really need to minmax my space, so uh yea. 
![image](https://github.com/user-attachments/assets/28052028-8102-43e9-bb70-63476d568ec6)
this might work.
i realised that the divebase tubes that i'm currently using don't have holes on the side, so that's fun. i'm going to have to redo it later.
![image](https://github.com/user-attachments/assets/ef63da24-142a-49a6-b8df-953e2be0d96e)
nearly 180 degrees.

# session 10:
![image](https://github.com/user-attachments/assets/7bac0c3d-3ab0-468f-b75e-69324b7f34ce)
i think that 1678 used a bolt here to hold the shaft, so that they can have the intake rotate around it, i think i'll take this idea and use it. 
i think they also have bearing holes so that the intake plate can rotate. 
![image](https://github.com/user-attachments/assets/4eb906dd-b640-4299-b34c-dafbb2b7d16f)
i should've merged the intake bearings and the intake plate sketch together. huhujaf;skldasfd
turns out that i've been using master sketches wrong... asjfkl;asjdf;asdf
these master sketches confuse me. 
appaently i needed to also include the starting maximum configuration limit. (kinda like the extension limit box, but you robot has to be able to fit in it when all of the things that can extend aren't extended), but surely it's fine. 
![image](https://github.com/user-attachments/assets/233da989-01a4-48fa-8a56-edef2f9f6609)
i feel like there's something missing here, but i'm not sure what it is.
i guess i'll move onto assembling it, and then seeing what's wrong. 
ah ok nevermind, i think i need to make it more parametric, so i can insert it into the assembly as a rigid, but also there's just another thing that's missing, that i don't really know what it is. 
ok wait i think i'm missing the rollers, the shafts, and the thing that allows the rollers to connect to the shaft. i think i might design them myself. 
![image](https://github.com/user-attachments/assets/465d4d8c-76f0-4040-8dc7-615dd473f348)
hmmmmmm ok.
![image](https://github.com/user-attachments/assets/a7d48d65-6cf0-4adf-a454-f3afb87dffde)
i mighttt make the rollers a bit thicker. 
![image](https://github.com/user-attachments/assets/35916d47-4d17-408f-8268-1ab1555102cd)
now i gotta add a hole. 
![image](https://github.com/user-attachments/assets/ea97e602-6916-4c83-b2d1-7c50aeb7d2f7)
wait a minute...
it makes sense now, they somehow joined the pulley to the plug/adapter that goes into the shaft, and they also aren't using a hex shaft, but using a circular shaft. hmmmmmmmmmmmm.
this... is quite the setback. 
i mean it's 100% possible for me to do this, but...
like, i could just fasten a pulley and call it a day, OR, i could just do some funny ideas that i can think of.
i think i'll take the funny ideas. 
problem is, i don't have any right now.
(200000 years later)
ok, so i think i'll keep things as they are, but i think i'll just use a normal pulley setup to transfer power and stuff. 
![image](https://github.com/user-attachments/assets/26d689a6-55cb-4f52-90ee-887758400b6c)
![image](https://github.com/user-attachments/assets/b5e610c6-3113-4d06-aca8-8c010df83663)
tis was an easy fix though. 
![image](https://github.com/user-attachments/assets/90ff6fab-6459-4b81-8df8-12db524bb1eb)
i realised that i need a shaft here, and a space between the blue plate and the grey plate for the flange of the bearing. 
![image](https://github.com/user-attachments/assets/f47428bb-bd11-4fa7-b975-43f3ddc6843e)
i reversed the direction of the extrude and made it thicker, but some problems arose. 
i fixed it quickly, and made the adjustments.
i also realised that i needed fillets on a bunch of edges. 
agh i just realised i need belts for the pulleys.
i'm very smart.
also, i just realised that i haven't even figured out any gear ratios for intaking...
i'm extremely smart. 
i think i'll go with a 10:1 or something. 
now, the next thing i gotta work out is the placement of the motor... i could mount it directly onto the arm, and i don't really have space on the drivebaes to mount it, so i guess that's the placement of the motor locked in. also, i think i might need to expand the size of the arm, to accomodate for the motor. 
![image](https://github.com/user-attachments/assets/deb3f209-9902-4611-874b-111093d70d83)
i also gotta make these things to deflect the notes inwards. 

# session 11:
well, lots of things to do. 
hmmmm i think i'll start with the gears that i'll  be using and mounting options and stuff like that. 
https://wcproducts.com/collections/belts-chain-gears/products/aluminum-hex-bore-gears
i looked through WCP's gears, and decided on a 12 tooth motor pinion into a 48 tooth gear which also turns a 20 tooth gear that goes to a 44 or 46 tooth gear, whcih is around 10:1.
![image](https://github.com/user-attachments/assets/d0c5a135-999b-419f-aeef-9d7841b707f9)
well i guess i don't need to make the arm larger. 
i think a 10:1 might be overkill, but idk. 
![image](https://github.com/user-attachments/assets/4287aae3-f241-4acd-9d65-789bce2fa2a2)
interestingly, 1678 has quite a low gear ratio, and also changes the ratio depending on the rollers. 
i think i'll lower my ratio to 5:1, but the ratio changing depending on the rollers is probably something i won't do, i assume it's to intake it more efficiently. 
i think i want to use a 12 tooth to a 36 tooth, then a 20 tooth to a 34 tooth. although, i could also use pulleys to skip the 20 tooth to 34 tooth part. i could use a 24 tooth pulley to a 36 tooth...
hmmm i think i'll do that. 
i may also swap to a 40 tooth gear. 
![image](https://github.com/user-attachments/assets/27e049f0-df2e-4f17-af96-2e22430e3e5b)
wait, it wasn't coincident to the circle? (always has been)
![image](https://github.com/user-attachments/assets/336b96d0-f625-4603-bb62-7d171bc44fce)
ayeeeee ok. (i don't know what i was doing before tbh)
![image](https://github.com/user-attachments/assets/49e53492-2891-4d15-b490-0b3e54961031)
i realised that i needed some standoffs on the other side, or it'd be unbalanced and things would be wacky, i tried making the circle larger, but it didn't work. 
![image](https://github.com/user-attachments/assets/a7c26f8a-4694-466c-8e94-55a92b62cf3f)
i adjusted it to this so it should work (it did)
i quickly created some new standoffs and then started to assemble everything again. 
oh wait nvm i realised that i need some other parts, specifically the one that deflects things. i think the thingy that deflects the notes in is 3d printed (how else would it be made i guess)
![image](https://github.com/user-attachments/assets/84f3a0de-95ba-4c6a-8e26-da1b45825401)
i think it should go between these belts. 
now i kinda need to see how big the deflecters need to be. 
it's 632 mm from one side of the intake to the other side. now i need to check the diameter of the note, from memory i think it's 14 inches, but i'm not sure. 
![image](https://github.com/user-attachments/assets/1ffcb32b-0e9c-4424-8aa7-84ed04573b69)
i was right 😎
ok, so 14 inches is around 36 centimetres, and that leaves aound 260 millimetres left over. this kinda means taht i'd eithe have to make the deflecty bit 13 cm on each side, (which is quite big) or i could make the indexing area larger and make it slowly go towards the middle. i could also use mecanums in some areas to help center it. i'm not sure what i want to do, obviously making the defleccty bit larger is the easist way to do it
hmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmmm.
i don't really know how to make the indexing area center things, so uh yeah. 
actually i looked at 1678's cad, and i realised that they don't even have any centering things on their indexer, and then i realised that i'm incredibly stupid, and that you don't actually need to fully center it, well i mean you could...
ok nevermind, i'm actually really dumb, because i checked the distance between their shooter plates, and realised that it's exactly 14 inches. 
huhuhajsfkldja;sdfja;skldfj;asd
i measured their indexer plate gap and it's like 15.25 inches. 
hmmmmm.
![image](https://github.com/user-attachments/assets/b6d1f68b-f972-4328-8a09-07491e662629)
well i mean if it works for them, surely it works for me. they leave around 3 inches of space between the thingys. 
at the time i wasn't sure if i would use a top down view to sketch out the deflector/centerer, but i ended up sketching on the intake plate. 
i also had to decide if i was to sketch on the deflector to remove some of it or use draft. i tried draft first, and it didn't really work out, i don't know what i expected.
![image](https://github.com/user-attachments/assets/471fad57-92aa-480d-8d07-dac391be8c0f)
![image](https://github.com/user-attachments/assets/eda2eacb-67f1-4a0d-8a3f-ec77d098510b)
hmmmm yes.

# session 12: 
![image](https://github.com/user-attachments/assets/c543a844-2079-4e4a-9433-cad24dc06ebb)
assemblyied
i realised that i hadn't made one of the shafts yet. 
![image](https://github.com/user-attachments/assets/6b0299e1-4a49-49d9-8641-e3fcc2ac7899)
oh.
![image](https://github.com/user-attachments/assets/a42cfcb0-d33a-42d2-92c4-f706836f003d)
had to adjust some positions. 
![image](https://github.com/user-attachments/assets/4d81b3ea-179b-42ce-beb0-1b8964e494a7)
uhhhhhhhhhhhhhhhhhhhhhhhhhhhhhhh.
![image](https://github.com/user-attachments/assets/9a3abefc-38bc-4b25-b052-750a1cfab39b)
i was wondeing why i had a lot of space in the sketch, then i ealised that i was using the wrong pulley. yippppeeeeee.
![image](https://github.com/user-attachments/assets/af9a795d-039d-47e9-977c-4dc0f0c1d774)
my god i'm dumb. 
![image](https://github.com/user-attachments/assets/14eedf67-4b4a-400e-bccc-d5f71546cb3e)
hmmmmmmmmmmmm.
so i also forgot the mate connectors for the belts.
yippeeee.
![image](https://github.com/user-attachments/assets/a53d6757-ef03-45e9-8b88-0e21fb215c42)
goofy mate connector. (usually it's in the middle of the hole, but it's on the edge/outer rim ???)
![image](https://github.com/user-attachments/assets/da08b74b-205a-4ebb-8583-2b705e500275)
slightlyyy clips into the pulley.
![image](https://github.com/user-attachments/assets/3170a177-145e-41b4-b2d6-0224c83e811b)
that works. 
![image](https://github.com/user-attachments/assets/2cb94267-8d76-4a9b-a663-e4125ccd19c0)
oh noeeeeeeeee
at the time i couldn't really figure out how to fix it,  until i looked through all sketches that were related to the adapter, and found out that i should've turned the hexagon. epic.
![image](https://github.com/user-attachments/assets/e59b7bd5-5569-4caa-a922-1aaca2ab9ee8)
uhhhhhhhhhhhhhhhh.
turns out i forgot to adjust for the pulley. rookie mistake D: 
i also made the shaft too long, rip. 
i was about to do the other side and then i realised that i hadn't put the holes on the other side. yipppeee.
ya might be wondering why there's less in the readmes, i'm currently trying to get into a better workflow of typing readmes and doing current cad work, and i leave out space between the different stuff that happen/don't explain how i solve it sometimes so uh yea. 

# session 13:
i realised that i had put the wrong sized roller on the bearing, so that's fun. 
![Screenshot 2024-08-30 232946](https://github.com/user-attachments/assets/4d786efe-d77d-4766-94e0-fca5045a0e90)
bruh i forgot to put the hole on the other side of the roller D:
![Screenshot 2024-08-30 233648](https://github.com/user-attachments/assets/43f4b07c-c567-4a7c-a078-655cf4716069)
epic moment where i forgot to adjust for the rollers. 
at the time i think i wnated to adapt the shape of the deflector to the rollers and the belts, kinda like 1678. (yeah this robbot is becoming a copy and paste in a way)
but then i realised that i couldn't really adapt it to the belts or it could get really funky and weird. 
i guess i'm adapting it to the rollers only. 
![image](https://github.com/user-attachments/assets/9d2f689a-a9a9-4bfb-a5ed-34d0a5aff75a)
nealy eveything has been assembled. 
i need sprockets, pulleys and gears. 
![image](https://github.com/user-attachments/assets/c4a91a12-3e64-404f-9e09-35ae01580c58)
all the stuff has been assembled, although i don't think i've figurd out a place to put the 15 tooth sprocket. 
hmmmmmmmmmmmmm.
idk.
well that's a problem for later (current me)
i tried to start on the indexer but i just feel insanely burnt out already, like i just wnat to do anything but frc cadding. also, with the fact that i have no idea what i'm doing. 
