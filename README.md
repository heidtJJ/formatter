# Formatter
This is C program that formats a text so that it fits nicely into a given number of columns. The text formatter must right-justify an input text file so the right margins are aligned in a straight line. The number of columns or width is specified as part of the input.
<h3>A sample input file</h3>

Here is T.S. Eliot's poem <i><a href="as1/hollow.txt">Hollow Men</a></i> in free form.
<pre>
The Hollow Men.

We are the hollow men
We are the stuffed men
Leaning together
Headpiece filled with straw. Alas!
Our dried voices, when
We whisper together
Are quiet and meaningless
As wind in dry grass
Or rats' feet over broken glass
in our dry cellar

Shape without form, shade without colour,
Paralysed force, gesture without motion;

Those who have crossed
With direct eyes, to death's other Kingdom
Remember us --- if at all --- not as lost
Violent souls, but only
As the hollow men
The stuffed men.

Eyes I dare not meet in dreams
In death's dream kingdom
These do not appear:
There, the eyes are
Sunlight on a broken column
There, is a tree swinging
And voices are
In the wind's singing
More distant and more solemn
Than a fading star.

Let me be no nearer
In death's dream kingdom
Let me also wear
Such deliberate disguises
Rat's coat, crowskin, crossed staves
In a field
Behaving as the wind behaves
No nearer ---

Not that final meeting
In the twilight kingdom

This is the dead land
This is cactus land
Here the stone images
Are raised, here they receive
The supplication of a dead man's hand
Under the twinkle of a fading star.

Is it like this
In death's other kingdom
Waking alone
At the hour when we are
Trembling with tenderness
Lips that would kiss
Form prayers to broken stone.

The eyes are not here
There are no eyes here
In this valley of dying stars
In this hollow valley
This broken jaw of our lost kingdoms

In this last of meeting places
We grope together
And avoid speech
Gathered on this beach of the tumid river

Sightless, unless
The eyes reappear
As the perpetual star
Multifoliate rose
Of death's twilight kingdom
The hope only
Of empty men.

Here we go around the prickly pear
Prickly pear prickly pear
Here we go around the prickly pear
At five o'clock in the morning.

Between the idea
And the reality
Between the motion
And the act
Falls the Shadow
For Thine is the Kingdom

Between the conception
And the creation
Between the emotion
And the response
Falls the Shadow
Life is very long

Between the desire
And the spasm
Between the potency
And the existence
Between the essence
And the descent
Falls the Shadow
For Thine is the Kingdom

For Thine is
Life is
For Thine is the

This is the way the world ends
This is the way the world ends
This is the way the world ends
Not with a bang but with a whimper.

</pre>

<hr>

<h3>Compilation and run</h3>

Here is a sample compilation of a formatter program on our Linux polaris system:
	<pre>
	gcc -g -c formatter.c
	gcc -g -o formatter formatter.o
	./formatter hollow.txt hollow-20.txt 20 
	./formatter hollow.txt hollow-30.txt 30
	./formatter hollow.txt hollow-40.txt 40
	</pre>

The resulting output files are as follows: 
<a href="as1/hollow-20.txt">20-line</a>,
<a href="as1/hollow-30.txt">30-line</a>,
<a href="as1/hollow-40.txt">40-line</a> formats.
<br>
