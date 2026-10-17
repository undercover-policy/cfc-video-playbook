# Ready drawings (export pack)

Drawings from the CFC Motion Engine, saved as files for tools that cannot run code: Descript, Riverside, Canva,
Keynote, PowerPoint, print layouts. Every one is CFC's own work, drawn in code. Licence: see the main README.

- `png/` holds each drawing as a transparent PNG at 2x size. Use these first. They keep the glows and shading.
- `svg/` holds a traced SVG of the same drawing: flat colours, no glows. Use it when a tool needs to scale the
  drawing very large or change a colour. The full-frame gym background is PNG only.
- `manifest.json` lists every file, its size and the engine call that drew it.

## Which file to use

| Drawing | Files | Use it on |
|---|---|---|
| California State Capitol, west front | capitol-night, capitol-ink | night: dark backgrounds; ink: light backgrounds |
| Church with a steeple | church-night, church-ink | the same rule |
| 1930s California school with its flag | school-1930s-night, school-1930s-ink | the same rule |
| Main-street family business | shop-night, shop-ink | the same rule |
| Southern California high school | high-school-day, high-school-night | a light or a dark scene |
| Stadium light tower | light-tower (with glow), light-tower-plain | night scenes |
| High-school gym at night | gym-night | a full vertical background, 1080 x 1920 |
| Volleyball net, match ball, ball icon | volleyball-net, volleyball, volleyball-icon | sports stories |
| Finish arch | finish-arch, finish-arch-blank | blank: add your own word in the red banner |
| Podium | podium, podium-blank | blank: no place numbers |

## Rules that still apply

- No em dashes in any words you add on screen.
- The lit doors are gold on purpose: light points at the one place the story is about. Do not add glowing windows.
- Pink and blue figures are a story code for girls and a boy in sports stories only. CFC aqua means help or protection.
- Every number, quote and verse you put beside a drawing needs a source and a named reviewer.

## The asset library

251 drawings made in code, each by palette (day or ink, and night) as a transparent PNG in `png/` and a layered SVG in
`svg/` (each part a named group). Many also have two short clips in `clips/` (WebM with a clear background): the
drawing arriving, and its one story move. Empty bands are for your own words; no drawing carries lettering.

### Capitol and civic

- **State Capitol, west front** (`capitol`): ink, night. Arrives: draws itself on, outlines first, rising from the ground (D-085: 3.5 s), 3.5 s. Move: the U.S. flag rises up its pole, then the door lights, 2.4 s. Clips.
- **Capitol rotunda, inside** (`rotunda`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: a shaft of light falls from the oculus to the floor, 1.4 s. Clips.
- **Senate chamber (red)** (`senate-chamber`): ink, night. Arrives: draws itself on, the rows of desks building from the floor up, 2.4 s. Move: light falls on the rostrum, 1.2 s. Clips.
- **Assembly chamber (green)** (`assembly-chamber`): ink, night. Arrives: draws itself on, the rows of desks building from the floor up, 2.4 s. Move: light falls on the rostrum, 1.2 s. Clips.
- **Hearing room** (`hearing-room`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the witness microphones light and light falls on the witness table, 1.2 s. Clips.
- **Podium with microphones** (`lectern`): day, night. Arrives: rises from the floor, 0.9 s. Move: the microphones light, one after another, 1 s. Clips.
- **Gavel and block** (`gavel`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: lifts and strikes once, one small rebound, still, 1 s. Clips.
- **Vote board, aye and no** (`vote-board`): day, night. Arrives: opens down from its top edge, 0.9 s. Move: the rows light one by one, green aye and red no, then the two totals, 2.4 s. Clips.
- **Governor's desk and pen** (`gov-desk`): day, night. Arrives: draws on, outline then fill, 1.2 s. Move: the pen comes to the line and signs (a flowing stroke, no letters), then lifts away, 2.6 s. Clips.
- **Capitol steps and lawn (rallies)** (`capitol-steps`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the flag rises and the door lights, 2 s. Clips.
- **Courthouse (classical, generic)** (`courthouse`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the doors open and light comes out, 1.2 s. Clips.
- **U.S. Supreme Court** (`supreme-court`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the bronze doors open and light falls out of them, 1.4 s. Clips.
- **Courtroom** (`courtroom`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the gavel on the bench strikes once and a soft light falls on the bench, 1.4 s. Clips.
- **City hall (Spanish revival, generic)** (`city-hall`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the doors under the middle arch light, 1 s. Clips.
- **School-board meeting room** (`board-room`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the public-comment microphone lights, 1 s. Clips.
- **Ballot box** (`ballot-box`): day, night. Arrives: rises out of the ground, 0.9 s. Move: a ballot envelope slides into the slot, 1 s. Clips.
- **Voting booth** (`voting-booth`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the curtain draws closed, 1 s. Clips.
- **Mail ballot envelope** (`mail-ballot`): day, night. Arrives: slides in on its edge and settles, 0.8 s. Move: lifts away to the upper right, posted, 1.2 s. Clips.
- **Voting sticker (words slot)** (`sticker`): day, night. Arrives: stamps down and lands, 0.6 s. Move: a thumb presses it flat, 0.6 s. Clips.

### Documents

- **Bill** (`bill`): day, night. Arrives: slides in on its edge and settles, 0.9 s. Move: the pages fan out from the corner, 1 s. Clips.
- **Amended bill** (`bill-amended`): day, night. Arrives: slides in on its edge and settles, 0.9 s. Move: strikeouts draw across in red, then new lines open in, in blue, 2 s. Clips.
- **Signature line and pen** (`signature`): day, night. Arrives: slides in on its edge and settles, 0.8 s. Move: the pen comes to the line, signs a flowing stroke (no letters) and lifts away, 2.2 s. Clips.
- **Stamp, approved or vetoed** (`stamp`): day, night; versions mark. Arrives: drops in above the page, 0.7 s. Move: comes down, presses and lifts away; the mark is there, 1.2 s. Clips.
- **Petition** (`petition`): day, night. Arrives: draws on, outline then fill, 1 s. Move: the signatures fill line by line, 3 s. Clips.
- **Letter and envelope** (`letter`): day, night. Arrives: draws on, outline then fill, 1 s. Move: the letter slides in, the flap closes, the envelope flies off, 2.4 s. Clips.
- **Email (no app logo)** (`email`): day, night. Arrives: draws on, outline then fill (a card), 0.9 s. Move: the message types in, Send presses, the window lifts away, 2.6 s. Clips.
- **Text bubbles** (`bubbles`): day, night. Arrives: the bubbles pop in one after another, 1 s. Move: three dots appear once, then the new message pops in, 1.4 s. Clips.
- **Parental-consent form** (`consent-form`): day, night; versions empty, signed. Arrives: slides in on its edge and settles, 0.9 s. Move: signed: the box ticks and the parent signs; empty: a red ring draws round the box nobody was asked to tick, 1.8 s.
- **Report card (grade slots)** (`report-card`): day, night. Arrives: draws on, outline then fill, 1 s. Move: the grade boxes fill one by one, 1.6 s. Clips.
- **Textbook (cover slot)** (`textbook`): day, night. Arrives: drops onto the table, closed, 0.8 s. Move: the cover swings open to the first page, 1.2 s. Clips.
- **Library book (cover slot)** (`library-book`): day, night. Arrives: slides in from the side, as off a shelf, 0.8 s. Move: the cover swings open to the card pocket and the first page, 1.2 s. Clips.
- **Curriculum binder** (`binder`): day, night. Arrives: draws on, outline then fill, 1 s. Move: two pages flip over, then the rings snap open, 2.2 s. Clips.
- **Court opinion (seal slot)** (`opinion`): day, night. Arrives: unrolls downward from its top edge, 1 s. Move: the seal presses into place, 1 s. Clips.
- **Calendar page** (`calendar`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the top page lifts at its corner, tears free and falls away, 1.4 s. Clips.
- **Clipboard checklist** (`checklist`): day, night. Arrives: draws on, outline then fill, 1 s. Move: the ticks land one by one, 1.8 s. Clips.
- **Newspaper (headline slots)** (`newspaper`): day, night. Arrives: drops onto the table, folded, 0.8 s. Move: unfolds to the whole front page, 1 s. Clips.
- **Law books on a shelf** (`law-books`): day, night. Arrives: draws on, outline then fill, 1 s. Move: one volume slides up out of the row and turns to show its cover, 1.6 s. Clips.
- **ID documents: birth certificate, student ID** (`id-docs`): day, night; versions certificate, student-id. Arrives: slides in on its edge and settles, 0.8 s. Move: one field changes: struck through in red, a new value slides in, in blue, 1.4 s. Clips.

### Maps and flags

- **California outline** (`california`): day, night. Arrives: the coast and borders draw on, then the land floods in from the south, 2 s. Clips.
- **The 58 counties** (`counties`): day, night. Arrives: the outline draws on, the land floods in, then the county lines draw, 2.6 s. Move: one county (o.county, default Sacramento) lifts out in gold, 0.8 s. Clips.
- **California regions (seven groups of counties)** (`regions`): day, night. Arrives: the outline draws on, the regions fill in one after another, 2 s. Move: one region (o.region) lifts out in gold, 0.9 s. Clips.
- **The U.S. with California lifted out** (`us-map`): day, night. Arrives: the states fill in from west to east, 1.6 s. Move: California lifts out, rises and turns gold; its shadow stays, 1 s. Clips.
- **Map pins: place, church, school, Capitol** (`map-pin`): day, night; versions capitol, church, place, school. Arrives: drops, lands with a small squash and bounce, settles, 0.7 s. Move: one ring spreads from its tip, 1 s.
- **Route line on the map** (`route`): day, night. Arrives: the map draws on, 1.6 s. Move: the route draws from start to end and a pin drops there, 1.6 s. Clips.
- **Pulse ring** (`pulse`): day, night. Arrives: the dot pops in, 0.4 s. Move: one ring spreads from the dot and is gone (a second follows close behind), 1.2 s. Clips.
- **Spread county to county** (`county-spread`): day, night. Arrives: the outline draws on, the land floods in, the county lines draw, 2 s. Move: the counties light one after another outward from a starting county, 2.4 s. Clips.
- **State Senate districts (40)** (`senate-districts`): day, night. Arrives: the districts fill in, in number order, 2 s. Move: one district (o.district) lifts out in gold, 0.9 s. Clips.
- **Assembly districts (80)** (`assembly-districts`): day, night. Arrives: the districts fill in, in number order, 2 s. Move: one district (o.district) lifts out in gold, 0.9 s. Clips.
- **Congressional districts (52): the Prop 50 map or the 2021 map** (`congress-districts`): day, night; versions map2021. Arrives: the districts fill in, in number order, 2 s. Move: one district (o.district) lifts out in gold, 0.9 s.
- **U.S. flag on a pole** (`us-flag`): day, night. Arrives: hoisted up the pole, 1.6 s. Move: one ripple runs out to the fly and it settles, 1.6 s. Clips.
- **California flag on a pole** (`ca-flag`): day, night. Arrives: hoisted up the pole, 1.6 s. Move: one ripple runs out to the fly and it settles, 1.6 s. Clips.

### Places

- **White clapboard church** (`church`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2.4 s. Move: the door lights, 1 s. Clips.
- **Mission-style church** (`mission-church`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the top bell swings and the door lights, 1.6 s. Clips.
- **Modern worship center** (`worship-center`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the lights come on in the glass entry, bottom to top, 1.4 s. Clips.
- **Storefront church** (`storefront-church`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the door lights, 1 s. Clips.
- **Sanctuary inside** (`sanctuary`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: light falls on the cross: it warms to gold and the wall behind it glows softly, 1.6 s. Clips.
- **Pregnancy resource center** (`pregnancy-center`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the door opens and warm light comes out, 1.2 s. Clips.
- **Clinic** (`clinic`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the door lights, 1 s. Clips.
- **Hospital** (`hospital`): ink, night. Arrives: builds up floor by floor, 2 s. Move: one window lights (o.room), 1 s. Clips.
- **Ranch house** (`ranch-house`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the windows light one by one, then the door, 1.4 s. Clips.
- **Two-storey suburban house** (`house`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the windows light one by one, then the porch lamp, 2.2 s. Clips.
- **Apartment block** (`apartment`): ink, night. Arrives: builds up floor by floor, 1.6 s. Move: the windows light one by one, 2 s. Clips.
- **Craftsman bungalow** (`bungalow`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the porch light comes on, 1 s. Clips.
- **Kitchen table, inside** (`kitchen`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the lamp lights the table, 1.2 s. Clips.
- **Living room with a TV** (`living-room`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the TV comes on and lights the room, 1 s. Clips.
- **Elementary school with playground** (`elementary-school`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the entrance lights, 1 s. Clips.
- **Middle school** (`middle-school`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the entrance lights, 1 s. Clips.
- **Southern California public high school** (`high-school`): day, night. Arrives: draws on, outline then fill, 1.6 s. Move: the entrance lights and the flag lifts in the wind, 1.6 s. Clips.
- **1930s California public school** (`school-1930s`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2.4 s. Move: the flag runs up its pole, then the door lights, 2 s. Clips.
- **Classroom** (`classroom`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the clock’s minute hand moves on one minute, 0.8 s. Clips.
- **Locker room** (`locker-room`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: one locker door swings open, 1 s. Clips.
- **Restroom door signs (pictograms from the rig)** (`restroom`): day, night; versions all-gender, men, women. Arrives: draws on, outline then fill, 0.9 s. Move: the door opens a hand’s width, 0.8 s.
- **Library** (`library`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the lights come on inside, shelf by shelf, 1.4 s. Clips.
- **School bus** (`school-bus`): ink, night. Arrives: drives in from the right, its wheels turning, and stops, 1.6 s. Move: the lights flash on and the stop arm swings out, 1.2 s. Clips.
- **Track and field** (`track`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the finish tape stretches across the lanes, 1 s. Clips.
- **Pool lanes** (`pool`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: a swimmer’s wake runs down one lane, 1.6 s. Clips.
- **Softball diamond** (`softball-field`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the foul lines chalk out from home plate, 1.2 s. Clips.
- **Basketball court** (`basketball-court`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: a ball arcs into the hoop and the net swings, 1.4 s. Clips.
- **Wrestling mat** (`wrestling-mat`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: light falls on the wrestling circle, 1 s. Clips.
- **High-school gym (a vertical background)** (`gym`): day. Arrives: draws on, outline then fill, 1.6 s. Move: the view pans along the gym (the truss, windows and bleachers move at their own depths), 2.5 s. Clips.
- **Bakery** (`bakery`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the door lights, 1 s. Clips.
- **Print shop** (`print-shop`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the door lights, 1 s. Clips.
- **Wedding venue** (`wedding-venue`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the doors open and light comes out, 1.2 s. Clips.
- **Main-street shop (family business)** (`main-street-shop`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2.4 s. Move: the door lights, then the upper windows light one by one, 2 s. Clips.
- **Tower Bridge, Sacramento** (`tower-bridge`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the centre span lifts up the towers and comes back down, 2.4 s. Clips.
- **Sacramento skyline (generic towers, the dome, Tower Bridge)** (`sacramento-skyline`): ink, night. Arrives: rises from the ground, 1.4 s. Move: lights come on in the towers, a few at a time, 2 s. Clips.
- **Los Angeles skyline (City Hall, plain towers)** (`la-skyline`): ink, night. Arrives: rises from the ground, 1.4 s. Move: lights come on in the towers, a few at a time, 2 s. Clips.
- **San Francisco skyline (Golden Gate, plain towers)** (`sf-skyline`): ink, night. Arrives: rises from the ground, 1.4 s. Move: lights come on in the towers, a few at a time, 2 s. Clips.
- **Church briefing room (fellowship hall)** (`briefing-room`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the projector comes on and the screen lights, 1 s. Clips.
- **Gala ballroom** (`ballroom`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the candles light table by table, then a light falls on the stage, 2.4 s. Clips.
- **Pregnancy center inside** (`pregnancy-rooms`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the ultrasound screen lights (blank), then the lamp in the waiting room, 1.4 s. Clips.
- **Doctor's exam room** (`exam-room`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the exam light comes on and light falls on the table, 1 s. Clips.
- **Pharmacy counter** (`pharmacy`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the lamp over the pickup lights, 1 s. Clips.
- **Counselor's office** (`counselor-office`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the door swings shut, 1 s. Clips.
- **School nurse's office** (`nurse-office`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the privacy screen unfolds across the cot, 1.2 s. Clips.
- **Prison cell** (`prison-cell`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the barred door slides shut, 1.4 s. Clips.
- **Clinic hallway (blank door sign)** (`clinic-hall`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: one door lights from inside, 1.2 s. Clips.
- **Foster home: a suitcase at the door** (`foster-door`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the door opens and warm light falls out, 1.4 s. Clips.
- **Hotel hallway (blank room numbers)** (`hotel-hall`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: a strip of light shows under one door, 1.2 s. Clips.
- **Hospital room (emergency or maternity)** (`hospital-room`): ink, night; versions emergency, maternity. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the heartbeat line runs across the monitor, 1.6 s. Clips.
- **Lecture hall (blank screen)** (`lecture-hall`): ink, night. Arrives: draws itself on, outlines first, rising from the ground, 2 s. Move: the big screen lights, 1 s. Clips.

### Figures (from the rig)

- **Person standing** (`person-stand`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: shifts weight once and settles, 1 s. Clips.
- **Person walking** (`person-walk`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: walks across, two strides, and stops, 2 s. Clips.
- **Person running** (`person-run`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: runs across, three strides, 1.6 s. Clips.
- **Person at a desk** (`person-desk`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: writes, then looks up, 1.4 s. Clips.
- **Person kneeling in prayer** (`person-pray`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the hands come together and the head bows, 1.2 s. Clips.
- **Person raising a hand to vote** (`person-raise-hand`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: one hand rises, 0.8 s. Clips.
- **Person holding a sign (slot)** (`person-sign`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: lifts the sign high, 1 s. Clips.
- **Person applauding** (`person-applaud`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: claps three times, then holds, 1.2 s. Clips.
- **Person cheering** (`person-cheer`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: both arms go up, 0.8 s. Clips.
- **Person bowing the head** (`person-bow`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the head bows, the hands fold, 1 s. Clips.
- **Person looking up** (`person-look-up`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: a hand comes up to shade the eyes and the head lifts, 1 s. Clips.
- **Person shrugging** (`person-shrug`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: shrugs, palms up, and holds, 0.8 s. Clips.
- **Person pointing** (`person-point`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the arm rises to point, 0.8 s. Clips.
- **Family: two parents, two children** (`family-four`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: they draw together, 1.2 s. Clips.
- **Single parent and child** (`family-single`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the child steps to the parent’s side, 1 s.
- **Grandparents** (`grandparents`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: they lean toward each other, 1 s.
- **Mother expecting a baby** (`mother-expecting`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: a hand comes to rest on the belly, 1 s.
- **Parent holding a toddler** (`parent-toddler`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: lifts the toddler a little and settles, 1 s.
- **Congregation in pews** (`congregation`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: they rise to their feet, 1.6 s. Clips.
- **Crowd at a rally** (`rally-crowd`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the signs go up and the crowd cheers, 1.2 s. Clips.
- **Students at desks** (`students`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: one student raises a hand, 1 s.
- **Witness at the hearing table** (`witness`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: leans to the microphone and speaks with a gesture, 1.2 s.
- **Legislator at the dais (no likeness)** (`legislator`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: raises a hand to vote, 0.9 s. Clips.
- **Judge in a robe** (`judge`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: lifts the gavel and strikes once, 1 s.
- **Teacher at the board** (`teacher`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: points to the board, 0.8 s.
- **Pastor at the pulpit** (`pastor`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: opens the arms toward the people, 1 s.
- **Nurse with a clipboard** (`nurse`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: looks up from the clipboard, 0.9 s.

### Figures (sports code)

- **Athlete: runner** (`athlete-runner`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: sprints across, three strides, 1.4 s.
- **Athlete: swimmer** (`athlete-swimmer`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: one stroke: the arms change places, 1.4 s.
- **Athlete: volleyball spike** (`athlete-volleyball`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: the arm swings through and the ball flies down, 1 s.
- **Athlete: basketball shot** (`athlete-basketball`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: rises and the ball leaves the hands, 1 s.
- **Athlete: softball batter** (`athlete-softball`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: swings the bat through, 0.8 s.
- **Athlete: wrestler** (`athlete-wrestler`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: shoots forward low, 0.8 s.
- **Athlete: hurdler** (`athlete-hurdler`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: clears the hurdle, 1 s.
- **Athlete: weightlifter** (`athlete-lifter`): day, night; versions boy, girl. Arrives: draws on, outline then fill, 0.9 s. Move: drives the bar from the shoulders to overhead, 1 s.

### Concepts

- **Scales** (`scales`): day, night. Arrives: draws on, outline then fill, 1 s. Move: the beam tips to one side (o.side) and settles there, 1.6 s. Clips.
- **Shield (protection, aqua)** (`shield`): day, night. Arrives: rises into place in front and settles, 0.9 s. Move: takes a blow, gives a little and holds firm, 0.9 s. Clips.
- **Chain that breaks** (`chain`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the middle link breaks and the two ends drop apart, 1 s. Clips.
- **Door to light** (`door-light`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the door opens and light falls through onto the floor, 1.4 s. Clips.
- **Key and lock** (`key-lock`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the key turns in the underside, the shackle springs open, 1.6 s. Clips.
- **Steps** (`steps`): day, night. Arrives: each step rises out of the ground in turn, 1.2 s. Move: the top step lights, 0.9 s. Clips.
- **Ladder** (`ladder`): day, night. Arrives: rises from the ground, 0.9 s. Move: the fly section slides up, locking on each rung, 1.4 s. Clips.
- **Bridge (halves meet)** (`bridge`): day, night. Arrives: draws on, outline then fill (the halves raised), 0.9 s. Move: the two halves come down and meet in the middle, 1.6 s. Clips.
- **Wall (builds)** (`wall`): day, night. Arrives: builds up course by course, 1.4 s. Move: the last brick drops into the gap at the top, 1 s. Clips.
- **Fence and gate** (`fence-gate`): ink, night. Arrives: draws itself on, one line, 1.6 s. Move: the gate swings open, 1.2 s. Clips.
- **Crack (spreads)** (`crack`): ink, night. Arrives: draws itself on, one line, 1.6 s. Move: a crack runs down through the wall, branching as it goes, 1.4 s. Clips.
- **Threads (pull taut)** (`threads`): ink, night. Arrives: draws itself on, one line, 1.6 s. Move: the threads pull taut, one after another, 1.4 s. Clips.
- **Tug-of-war rope** (`rope`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the rope is pulled one way until the red tie crosses the mark, 1.4 s. Clips.
- **Compass (settles)** (`compass`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the needle swings and settles, 2 s. Clips.
- **Spotlight** (`spotlight`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: it comes on and a circle of light lands on the floor, 1.2 s. Clips.
- **Megaphone** (`megaphone`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: sound arcs pulse out of the bell three times, 1.6 s. Clips.
- **Magnifier over a page** (`magnifier`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the lens glides along a line and stops; the line is marked in gold, 1.8 s. Clips.
- **Puzzle pieces (join)** (`puzzle`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the two pieces slide together and join, 1.2 s. Clips.
- **Lightbulb (lights)** (`lightbulb`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: it flickers once and lights, 1.2 s. Clips.
- **Hourglass (sand runs)** (`hourglass`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the sand runs from the top to the bottom, 3 s. Clips.
- **Thermometer (rises)** (`thermometer`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the red rises to its level, 1.6 s. Clips.
- **Umbrella (protection, aqua)** (`umbrella`): day, night. Arrives: draws on, outline then fill (furled), 0.9 s. Move: opens from furled to full, with one small bounce, 1.2 s. Clips.
- **Anchor (drops)** (`anchor`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: it drops to the sea floor and settles, a puff of sand either side, 1.4 s. Clips.
- **Torch** (`torch`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the flame catches and rises, 1.4 s. Clips.
- **Latin cross** (`cross`): day, night. Arrives: rises up out of the ground, 1 s. Move: a soft light rises behind it, 1.6 s. Clips.
- **Open Bible** (`bible`): day, night. Arrives: draws on, outline then fill, 1 s. Move: a page lifts, arcs over the spine and settles, 1.2 s. Clips.
- **Wedding rings (link)** (`rings`): day, night. Arrives: draws on, outline then fill (apart), 0.9 s. Move: the two bands slide together and link; a glint, 1.4 s. Clips.
- **Heart (one line)** (`heart`): ink, night. Arrives: draws itself on, one line, 1.6 s. Move: beats once and fills with a warm light, 1.2 s. Clips.
- **House with a heart** (`house-heart`): ink, night. Arrives: draws itself on, one line, 1.6 s. Move: the heart beats once and glows warm, 1.2 s. Clips.
- **Crib** (`crib`): ink, night. Arrives: draws itself on, one line, 1.6 s. Move: the mobile turns once, 2 s. Clips.
- **Cradle (rocks once)** (`cradle`): ink, night. Arrives: draws itself on, one line, 1.6 s. Move: rocks once on its rockers, a damped swing, 2 s. Clips.
- **Ultrasound frame (blank)** (`ultrasound`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: one scan line sweeps across the blank fan, which brightens a little, 1.2 s. Clips.

### Objects

- **Smartphone: message, alert, call** (`phone`): day, night; versions alert, call, message. Arrives: slides up into place, 0.7 s. Move: the screen lights, the new message pops in, it buzzes once, 1.2 s.
- **Laptop (screen slot)** (`laptop`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the screen wakes, 1 s. Clips.
- **TV (screen slot)** (`tv`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: it turns on: a bright line opens to the full screen, 0.8 s. Clips.
- **Microphone on a stand** (`mic-stand`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: sound rings spread from the microphone once, 1.2 s. Clips.
- **Camera on a tripod** (`camera-tripod`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the record light comes on: one blink, then steady, 1 s. Clips.
- **Backpack** (`backpack`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the zipper pull runs along the front pocket, 1 s. Clips.
- **Trophy (plate slot)** (`trophy`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: a shine sweeps across the cup, 1 s. Clips.
- **Medal** (`medal`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: it swings once and settles, 1.4 s. Clips.
- **Stopwatch** (`stopwatch`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: press, the hand sweeps most of a turn, press, it stops, 2.4 s. Clips.
- **Whistle** (`whistle`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: three short blasts of sound lines, 1.5 s. Clips.
- **Balls (basketball, softball, soccer)** (`balls`): day, night; versions basketball, soccer, softball. Arrives: draws on, outline then fill, 0.9 s. Move: it bounces twice, lower each time, and settles, 1.4 s. Clips.
- **Money** (`money`): day, night. Arrives: the notes land one by one, 1 s. Move: three more notes drop onto the pile, 1.2 s. Clips.
- **Tax-dollar coin** (`coin`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: it flips twice in the air and lands, 1.2 s. Clips.
- **Coin jar** (`coin-jar`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: a coin drops through the slot onto the pile, 1.2 s. Clips.
- **Coffee mug** (`coffee`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: steam rises and curls away, 2.2 s. Clips.
- **Car (generic sedan)** (`car`): day, night. Arrives: drives in from the side, 1 s. Move: the headlights come on, 0.8 s. Clips.
- **Curbside mailbox** (`mailbox`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the red flag swings up, 1 s. Clips.
- **House keys** (`keys`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: they jingle, swing and settle, 1.6 s. Clips.
- **Candle** (`candle`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the flame catches, flickers once and steadies, 1.4 s. Clips.
- **Church bell** (`bell`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: it swings out and back, ringing at each end, 2 s. Clips.
- **Hymnal** (`hymnal`): day, night. Arrives: drops onto the table, closed, 0.8 s. Move: the cover swings open to a page of staves and notes, 1.2 s. Clips.
- **Pew Bible in its rack** (`pew-rack`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the Bible is drawn halfway up out of the rack, 1.2 s. Clips.
- **Pill bottle and blister pack** (`pills`): day, night; versions both, bottle, pack. Arrives: drops in and settles, 0.7 s. Move: the cap twists, lifts off and is set down beside the bottle, 1.4 s. Clips.
- **Bedside with a pill bottle** (`bedside`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the lamp slowly dims, 2 s. Clips.
- **Insurance card (slots)** (`insurance-card`): day, night; versions gold, red. Arrives: slides in on its edge and settles, 0.7 s. Move: one coverage line is marked (gold, or struck in red), 1 s. Clips.
- **Police car (no lettering)** (`police-car`): day, night. Arrives: drives in from the side, 1 s. Move: the light bar flashes red and blue, twice, 1.6 s. Clips.
- **Safe-surrender baby box (blank sign)** (`baby-box`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the hatch swings open on a warm, lit bassinet, 1.6 s. Clips.
- **IVF lab bench** (`ivf-bench`): day, night. Arrives: draws on, outline then fill, 0.9 s. Move: the microscope light comes on and a round cell shows on the monitor, 1.2 s. Clips.

### Data and on-screen

- **Stat tile** (`stat-tile`): day, night. Arrives: pops: grows past full size and settles (FB-019), 0.5 s. Move: an underline draws under the number, 0.6 s. Clips.
- **Counter (split-flap digits, true values only)** (`counter`): day, night. Arrives: pops in and settles, 0.5 s. Move: the flaps fall one by one, each showing its final digit, 1.6 s. Clips.
- **Bar chart (values from the project)** (`bar-chart`): day, night. Arrives: pops in and settles, 0.5 s. Move: the bars grow to their values, left to right, 1.4 s. Clips.
- **Line chart (values from the project)** (`line-chart`): day, night. Arrives: pops in and settles, 0.5 s. Move: the line draws from first point to last; the last point lands in gold, 1.6 s. Clips.
- **Donut chart (parts from the project)** (`donut`): day, night. Arrives: pops in and settles, 0.5 s. Move: the parts sweep round in turn, 1.4 s. Clips.
- **Poll result (shares from the project)** (`poll`): day, night. Arrives: pops in and settles, 0.5 s. Move: the bars fill to their shares, 1.2 s. Clips.
- **Vote tally (counts from the project)** (`vote-tally`): day, night. Arrives: pops in and settles, 0.5 s. Move: the seats fill in, ayes and noes together, 1.6 s. Clips.
- **Timeline** (`timeline`): day, night. Arrives: the line draws and each point pops in as the line reaches it, 1.4 s. Move: the highlight moves on to the next point, 0.9 s. Clips.
- **Timeline, tall (vertical video)** (`timeline-tall`): day, night. Arrives: the line draws down and each point pops in as the line reaches it, 1.4 s. Move: the highlight moves on to the next point, 0.9 s.
- **Quote frame** (`quote-frame`): day, night. Arrives: pops in and settles, 0.5 s. Move: the accent bar draws down the left edge, 0.9 s. Clips.
- **Callout pill with a leader line** (`callout`): day, night. Arrives: pops in and settles, 0.5 s. Move: the leader line draws out to the thing it names, 1 s. Clips.
- **Call to action: Call, Email, Testify, Sign, Give** (`cta`): day, night; versions call, email, give, sign, testify. Arrives: draws on, outline then fill, 0.9 s. Move: presses in once and springs back, 0.7 s. Clips.
- **QR frame (a slot for a real code)** (`qr-frame`): day, night. Arrives: pops in and settles, 0.5 s. Move: the corner brackets close in on the code, 0.8 s. Clips.
- **End card frame, tall** (`end-card`): day, night; versions qr. Arrives: draws on, outline then fill, 1 s. Move: a gold underline draws under the web address, 0.8 s. Clips.
- **End card frame, wide** (`end-card-wide`): day, night; versions qr. Arrives: draws on, outline then fill, 1 s. Move: a gold underline draws under the web address, 0.8 s.
- **Lower third (only with a presenter on screen)** (`lower-third`): day, night. Arrives: slides in from the left and settles, 0.7 s. Move: the accent line runs under the name, 0.8 s. Clips.
- **Bill path track** (`bill-path`): day, night; versions stopped, vetoed. Arrives: the track draws left to right and the stations pop in, 1.6 s. Move: the bill moves on one station and that station lights, 1.2 s. Clips.
- **Bill path track, tall (vertical video)** (`bill-path-tall`): day, night; versions stopped, vetoed. Arrives: the track draws down and the stations pop in, 1.6 s. Move: the bill moves on one station and that station lights, 1.2 s.
- **Social-media feed with an age check** (`feed`): day, night. Arrives: the posts slide up one after another, 1.2 s. Move: the feed dims and an age check pops up over it, 1.2 s. Clips.
- **Mandatory training on a screen** (`training`): day, night. Arrives: draws on, outline then fill (a card), 0.9 s. Move: the progress bar fills, the module ticks, the next one becomes current, 1.6 s. Clips.
- **Chatbot window (no product look)** (`chatbot`): day, night. Arrives: draws on, outline then fill (a card), 0.9 s. Move: three dots, then the helper’s reply types in line by line, 1.8 s. Clips.

### Backgrounds

- **Capitol lawn, wide** (`bg-capitol-lawn`): day, night; versions dawn, day. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Capitol lawn, tall** (`bg-capitol-lawn-tall`): day, night; versions dawn, day. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Capitol steps with a crowd area, wide** (`bg-capitol-steps`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Capitol steps with a crowd area, tall** (`bg-capitol-steps-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Hearing room, wide** (`bg-hearing-room`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Hearing room, tall** (`bg-hearing-room-tall`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Sanctuary, wide** (`bg-sanctuary`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Sanctuary, tall** (`bg-sanctuary-tall`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Classroom, wide** (`bg-classroom`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Classroom, tall** (`bg-classroom-tall`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Kitchen table, wide** (`bg-kitchen-table`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Kitchen table, tall** (`bg-kitchen-table-tall`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Suburban street, wide** (`bg-suburban-street`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Suburban street, tall** (`bg-suburban-street-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Campus (high school), wide** (`bg-campus`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Campus (high school), tall** (`bg-campus-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Field and track, wide** (`bg-field-track`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Field and track, tall** (`bg-field-track-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Gym, wide** (`bg-gym`): day. Arrives: the gym comes up into place, 1 s. Move: the view pans along the gym (truss, windows and bleachers at their own depths), 3 s.
- **Gym, tall** (`bg-gym-tall`): day. Arrives: the gym comes up into place, 1 s. Move: the view pans along the gym (truss, windows and bleachers at their own depths), 3 s.
- **Courtroom, wide** (`bg-courtroom`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Courtroom, tall** (`bg-courtroom-tall`): day, night. Arrives: the room comes up into place, 1 s. Move: the view drifts sideways, 3 s.
- **Sacramento skyline, wide** (`bg-sacramento`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Sacramento skyline, tall** (`bg-sacramento-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Coast and ocean, wide** (`bg-coast`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Coast and ocean, tall** (`bg-coast-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Golden hills, wide** (`bg-golden-hills`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Golden hills, tall** (`bg-golden-hills-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Central Valley farm rows, wide** (`bg-farm-rows`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Central Valley farm rows, tall** (`bg-farm-rows-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Desert, wide** (`bg-desert`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Desert, tall** (`bg-desert-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Sierra peaks, wide** (`bg-sierra`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
- **Sierra peaks, tall** (`bg-sierra-tall`): day, night. Arrives: builds layer by layer, the far land first, 1.8 s. Move: the view drifts sideways, near layers faster, 3 s.
