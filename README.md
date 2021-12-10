# Fender Mustang II open back replacement in FreeCAD
Bart Massey 2021

Here is FreeCAD source for a laser-cuttable open back I
designed for the Fender Mustang II guitar amp. Also included
are PDF and DXF files; hopefully this will be something you
can feed to your laser cutter as I did.

![Mustang II open back](mustang-ii-open-back.jpg)

**Note:** This project is actually several years old, and I
can't vouch for its current status: I *think* this will
still cut to something that will fit perfectly, but I
haven't checked it. FreeCAD has changed a lot since I
actually built this and I've cleaned up accordingly;
hopefuly I didn't break something in the process. *Caveat
emptor,* your mileage may vary, *etc.*

## Background

This is a design for a replacement back for the
[Fender Mustang II](https://www.gearank.com/gear/fender-mustang-ii-v2)
guitar amplifier. (The amp I modified is a V1, but as far as
I know the V2 has the same back and the same issues.) The
Mustang II is a 40W transistor amp with a reasonable set of
built in digital effects and amp/cabinet emulations.

The biggest drawback of the Mustang II that it just doesn't
sound as good as the Mustang III. A friend and I were
playing with this, and concluded that replacing the closed
Mustang II back with a Mustang III-style open back and
replacing the Mustang II speaker with the model used in the
Mustang III improved the sound of the Mustang II *a lot.*

There's a theory going around that the modeling software in
the Mustang II and Mustang III are identical, and that thus
the Mustang II speaker and cabinet are mismatched with the
modeling. Our experiments seem to confirm this theory.  The
Mustang II is cheaper and simpler to operate than the
Mustang III. The Mustang II is currently US$100-$150 used on
[Reverb.com](http://reverb.com); Mustang III used prices are
quite variable, but range from $50 to $100 more. I think
upgrading the Mustang II was worth it, but it's a close call
these days.

## How To Do This

You are probably planning to upgrade the speaker
(recommended).  The Mustang III apparently uses a Celestion
G12T-H100 (8Ω), and that definitely sounds really good with
the modeling functions in my Mustang II. The G12T is about
US$120 new and about half that used (as of this writing). I
also have tried an Eminence Cannabis Rex 12", which is
similarly priced and I think sounds better (it is one of my
favorite speakers period). The C-Rex isn't as close to
accurate as the G12T when the Mustang II modeling is used:
however, the modeling is a bit meh either way.

Check that the dimensions and screw hole positions I
measured for my old back match yours. The easiest way to do
that is to get out FreeCAD, grab a tape measure, and
compare.  If the dimensions don't match really closely I'd
recommend adjusting them before cutting. If the screw holes
don't match you can either adjust those before cutting or
just drill new pilot holes as you switch backs.

You'll need access to a big-enough laser cutter: the end
result is 17″×16″, and you'll want at least an inch of slack
above that. Get a 1/8″ or 3/16″ panel from a hobby store.
Use wood or plywood, not composite: composite won't be
strong and may emit toxic fumes when laser cut.

Cut the panel in multiple passes at highest power: keep the
laser moving fast. (Only an idiot would try to do it in one
pass and set a panel on fire — I didn't do that even once,
no siree.)

Once the panel is cut, prime it if desired, then paint it
with one or two coats of durable flat black paint. I think I
brushed mine: spraying should also work.

Next, get some speaker cloth (easily found online) and
hot-glue or staple it inside to cover the holes. This will
prevent junk from coming in, and sholdn't affect the sound.

If you like, take a picture of the Fender labels from the
old back, laser print them, cut them out, and glue them to
the new back.

Unscrew your old back and replace the speaker as
desired. Then screw in your new back using the existing
screws, cutting pilot holes first if needed.

If you need replacement screws and cup washers for some
reason (I can imagine some idiot losing them all at some
point, but of course not me because I'm better than that,
for sure), Mojotone sells
[washers](https://www.mojotone.com/Black-Oxide-Large-Decorative-Washers)
and
[screws](https://www.mojotone.com/Black-Backpanel-Screws-for-Open-Back-Cabs-1-1-4_2)
that are perfect replacements and really reasonably
priced. That said, any #6×¼″ wood screws will probably work
OK.

Now enjoy your new setup!

## Licensing

The work here is made available under the "CC-BY-3.0
License". Please see the file `LICENSE` in this distribution
for license terms.
