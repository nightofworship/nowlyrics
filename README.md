Help me convert plain text lyrics to OpenLP formatted lyrics. Be sure to follow XML syntax.

Use the level of care and attention that Thomas A. Dorsey, Andraé Crouch, or Percy Bady would have while formatting song lyrics.

The purpose of this conversion is to display the lyrics on a large projector at the front and back of the sanctuary as a reminder to the choir and praise team. Ad libs are not helpful in this context and should be removed if easily identified. Err on the side of caution when removing text. We want lyrics verbatim but formatted correctly. The ideal output is lyrics that are easy to read and follow along with. Be mindful not to include too many lyrics in the same line or lines on the same slide. Try to keep it simple for Title and Author, they will not be displayed on the slides.

Verse types:
- Verse
- Chorus
- Bridge
- Pre-Chorus
- Intro
- Ending
- Other

The following are not perfect examples but should give you a good idea of how to format the lyrics.

Example:
<plain_text_lyrics>
BJ Putnam
Healing Is Here

Healing is here
Healing is here
Healing is here
And I recieve it
Healing is here
Healing is here
Healing is here
And I believe it
And I reach my hands
To the heavens
I lift my eyes where my help comes from
I look to You my rock my healer
I trust in You
Freedom is here
Freedom is here
Freedom is here
And I recieve it
Freedom is here
Freedom is here
Freedom is here
And I believe it
And I reach my hands
To the heavens
I lift my eyes where my help comes from
I look to You my rock my healer
I trust in You
Sickness can′t stay any longer
Your perfect love is casting out fear
You are the God of all power
And it is Your will that my life is healed
And I reach my hands
To the heavens
I lift my eyes where my help comes from
I look to You my rock my healer
I trust in You
Instrumental
We lift our hands to You
We lift our voices oh God
You have never failed
And You never will
You have never failed
And You never will
You have never failed
And You never will
You have never failed
And You never will
And I reach my hands
To the heavens
I lift my eyes where my help comes from
I look to You my rock my healer
I trust in You
</plain_text_lyrics>

<formatted_lyrics>
<?xml version='1.0' encoding='UTF-8'?>
<song xmlns="http://openlyrics.info/namespace/2009/song" version="0.8" createdIn="OpenLP 3.1.7" modifiedIn="OpenLP 3.1.7" modifiedDate="2025-10-28T18:16:06">
  <properties>
    <titles>
      <title>Healing Is Here</title>
      <title>Healing Is Here (feat. Nicole Binion)</title>
    </titles>
    <authors>
      <author>BJ Putnam</author>
    </authors>
  </properties>
  <lyrics>
    <verse name="v1">
      <lines>Healing is here, healing is here<br/>Healing is here and I receive it<br/>Healing is here, healing is here<br/>Healing is here and I believe it</lines>
    </verse>
    <verse name="c1">
      <lines>I reach my hands to the heavens<br/>I lift my eyes where my help comes from<br/>I look to You my rock my healer<br/>I trust in You</lines>
    </verse>
    <verse name="v2">
      <lines>Freedom is here, freedom is here<br/>Freedom is here and I receive it<br/>Freedom is here, freedom is here<br/>Freedom is here and I believe it</lines>
    </verse>
    <verse name="c2">
      <lines>I reach my hands to the heavens<br/>I lift my eyes where my help comes from<br/>I look to You my rock my healer<br/>I trust in You<br/><p style="page-break-after: always;"/><br/>I reach my hands to the heavens<br/>I lift my eyes where my help comes from<br/>I look to You my rock my healer<br/>I trust in You</lines>
    </verse>
    <verse name="b1">
      <lines>Sickness can't stay any longer<br/>Your perfect love is casting out fear<br/>You are the God of all power<br/>And it is Your will that my life is healed</lines>
    </verse>
    <verse name="b2">
      <lines>Sickness can't stay any longer<br/>Your perfect love is casting out fear<br/>You are the God of all power<br/>And it is Your will that my life is healed<br/><p style="page-break-after: always;"/><br/>Sickness can't stay any longer<br/>Your perfect love is casting out fear<br/>You are the God of all power<br/>And it is Your will that my life is healed<br/><p style="page-break-after: always;"/><br/>Sickness can't stay any longer<br/>Your perfect love is casting out fear<br/>You are the God of all power<br/>And it is Your will that my life is healed</lines>
    </verse>
    <verse name="c3">
      <lines>I reach my hands to the heavens<br/>I lift my eyes where my help comes from<br/>I look to You my rock my healer<br/>I trust in You<br/><p style="page-break-after: always;"/><br/>I reach my hands to the heavens<br/>I lift my eyes where my help comes from<br/>I look to You my rock my healer<br/>I trust in You</lines>
    </verse>
    <verse name="o1">
      <lines>We lift our hands to You<br/>We lift our voices, oh God<br/><p style="page-break-after: always;"/><br/>You have never failed and You never will<br/>You have never failed and You never will<br/>You have never failed and You never will<br/>You have never failed and You never will</lines>
    </verse>
    <verse name="e1">
      <lines>I reach my hands to the heavens<br/>I lift my eyes where my help comes from<br/>I look to You my rock my healer<br/>I trust in You</lines>
    </verse>
  </lyrics>
</song>

</formatted_lyrics>


Example:
<plain_text_lyrics>
I Thank God
Housefires, Maverick City Music, and UPPERROOM

Wandering into the night
Wanting a place to hide
This weary soul, this bag of bones
I tried with all my might
But I just can't win the fight
I'm slowly drifting
Oh, vagabond
And just when I ran out of road
I met a man I didn't know
And he told me that I was not alone (no)
He picked me up (hey)
He turned me around (hey)
And placed my feet on solid ground
I thank the Master
I thank the Savior
Because He healed my heart
And changed my name
Forever free, I am not the same
I thank the Master
I thank the Savior
I thank God
I cannot deny what I've see (oh, no, no)
Got no choice but to believe
My doubts are burning
Ohh, like ashes in the wind
So, so long to my old friends
Burden and bitterness
You can just keep them moving
For you ain't welcome here (you ain't welcome here)
From now 'til I walk the streets of gold
I'll sing of how You saved my soul
This wayward son has found his way back home
He picked me up (hey)
He turned me around
He placed my feet on solid ground
I thank the Master
I thank the Savior
Because He healed my heart
And changed my name
Forever free, I'm not the same
I thank the Master
I thank the Savior
Oh, I thank God
Hell lost another one, I am free (I am free)
Oh, I am free (oh, I am free), oh, I am free
Hell lost another one, I am free (oh, I am free)
I am free (I am free), oh, I am free
Hell lost another one, I am free (oh, I am free)
Oh, I am free (yes), I am free
Hell lost another one, I am free (oh, I am free)
Oh, I am free (I am free)
He picked me up (picked me up)
He turned me around
He placed my feet on solid ground
I thank the Master
I thank the Savior
Because He healed my heart (healed my heart)
He changed my name
Forever free, I'm not the same
I thank the Master
I thank the Savior
I thank God
Get up, get up, get up
Get up out of that grave
Get up, get up, get up (hey)
Get up out of that grave
Get up, get up, get up (hey)
Get up out of that grave (get up out of that grave)
Get up, get up, get up (hey)
Get up out of that grave
</plain_text_lyrics>

<formatted_lyrics>
<?xml version='1.0' encoding='UTF-8'?>
<song xmlns="http://openlyrics.info/namespace/2009/song" version="0.8" createdIn="OpenLP 3.1.7" modifiedIn="OpenLP 3.1.7" modifiedDate="2025-10-28T18:31:51">
  <properties>
    <titles>
      <title>I Thank God</title>
      <title>I Thank God (feat. Chuck Butler, Maryanne J. George, Dante Bowe &amp; Aaron Moses)</title>
    </titles>
    <authors>
      <author>Maverick City Music</author>
    </authors>
  </properties>
  <lyrics>
    <verse name="v1">
      <lines>Wandering into the night<br/>Wanting a place to hide<br/>This weary soul<br/>This bag of bones<br/><p style="page-break-after: always;"/><br/>And I try with all my might<br/>But I just can't win the fight<br/>I'm slowly drifting<br/>A vagabond</lines>
    </verse>
    <verse name="p1">
      <lines>And just when I ran out of road<br/>I met a man I didn't know<br/>And He told me that I was not alone</lines>
    </verse>
    <verse name="c1">
      <lines>He picked me up, He turned me around<br/>He placed my feet on solid ground<br/>I thank the Master, I thank the Savior<br/><p style="page-break-after: always;"/><br/>Because He healed my heart, He changed my name<br/>Forever free, I'm not the same<br/>I thank the Master, I thank the Savior<br/>I thank God</lines>
    </verse>
    <verse name="v2">
      <lines>I cannot deny what I see<br/>Got no choice but to believe<br/>My doubts are burning<br/>Like ashes in the wind<br/>So, so long to my old friends<br/><p style="page-break-after: always;"/><br/>Burden and bitterness<br/>You can just keep it moving, hey<br/>Nah, you ain't welcome here</lines>
    </verse>
    <verse name="p2">
      <lines>From now 'til I walk the streets of gold<br/>I'll sing of how You saved my soul<br/>This wayward son has found his way back home</lines>
    </verse>
    <verse name="c2">
      <lines>He picked me up, He turned me around<br/>Placed my feet on solid ground<br/>I thank the Master, I thank the Savior<br/><p style="page-break-after: always;"/><br/>Because He healed my heart, He changed my name<br/>Forever free, I'm not the same<br/>I thank the Master, I thank the Savior<br/>Oh, I thank God</lines>
    </verse>
    <verse name="o1">
      <lines>Oh, I thank God<br/>Oh, I thank God<br/>Oh, I thank God</lines>
    </verse>
    <verse name="b1">
      <lines>Oh, Hell lost another one, I am free<br/>I am free, I am free<br/>Hell lost another one, I am free<br/>I am free, I am free<br/><p style="page-break-after: always;"/><br/>Hell lost another one, oh, I am free<br/>I am free, yes, I am free<br/>Hell lost another one, I am free<br/>I am free, I am free<br/><p style="page-break-after: always;"/><br/>Hell lost another one, I am free<br/>I am free, oh, I am free<br/>Hell lost another one, I am free<br/>I am free, I am free<br/><p style="page-break-after: always;"/><br/>Hell lost another one, I am free<br/>Oh, I am free, oh, I am free<br/>Oh, Hell lost another one, I am free<br/>I am free, oh</lines>
    </verse>
    <verse name="b2">
      <lines>Get up, get up, get up<br/>Get up outta that grave<br/>Get up, get up, get up<br/>Get up outta that grave <br/>Get up, get up, get up, don't stay there <br/><p style="page-break-after: always;"/><br/>Get up outta that grave<br/>Get up, get up, get up, c'mon<br/>Get up outta, say, get up<br/>Get up, get up, get up outta that<br/>Get up outta that grave, get up, get up<br/><p style="page-break-after: always;"/><br/>Get up, get up, get up outta that grave<br/>Get up outta that grave, don't stay there</lines>
    </verse>
    <verse name="c3">
      <lines>He picked me up, turned me around<br/>Placed my feet on solid ground<br/>I thank the Master, I thank the Savior<br/><p style="page-break-after: always;"/><br/>Because He healed my heart, He changed my name<br/>Forever free, I'm not the same<br/>I thank the Master, I thank the Savior<br/>I thank God</lines>
    </verse>
    <verse name="c4">
      <lines>He picked me up, He turned me around<br/>He placed my feet on solid ground<br/>I thank the Master, I thank the Savior<br/><p style="page-break-after: always;"/><br/>Because He healed my heart, He changed my name<br/>Forever free, I am not the same<br/>I thank the Master, I thank the Savior<br/>I thank God<br/></lines>
    </verse>
    <verse name="o2">
      <lines>And if He did it for me, He can do it for you<br/>If He did it for me, He can do it for you</lines>
    </verse>
    <verse name="b3">
      <lines>Get up, get up, get up<br/>Get up outta that grave</lines>
    </verse>
    <verse name="o3">
      <lines>If He did it for me, He can do it for you<br/>If He did it for me, He can do it for you<br/>If He did it for me, He can do it for you<br/>The testimony of Jesus is the Spirit of prophecy<br/><p style="page-break-after: always;"/><br/>That means what He did for another, He can do it again<br/>That means what He did for another, He can do it again<br/>The testimony of Jesus is the Spirit of prophecy<br/>Is the Spirit of prophecy, is the Spirit of prophecy<br/><p style="page-break-after: always;"/><br/>That means what He did for another, He can do it again<br/>That means what He did for another, He can do it<br/>So we prophecy<br/></lines>
    </verse>
  </lyrics>
</song>

</formatted_lyrics>


Example:
<plain_text_lyrics>
Lion and the Lamb
Leeland

[Verse 1]
He’s coming on the clouds
Kings and kingdoms will bow down
Every chain will break
As broken hearts declare His praise
For who can stop the Lord Almighty?

[Chorus]
Our God is the Lion, the Lion of Judah
He’s roaring with power and fighting our battles
Every knee will bow before Him
Our God is the Lamb, the Lamb that was slain
For the sins of the world, His blood breaks the chains
And every knee will bow before the Lion and the Lamb
Oh, every knee will bow before Him

[Verse 2]
So open up the gates
Make way before the King of kings, woah, woah
The God who comes to save
Is here to set the captives free
For who can stop the Lord Almighty?

[Chorus]
And our God is the Lion, the Lion of Judah
He’s roaring with power and fighting our battles
Every knee will bow before Him
Our God is the Lamb, the Lamb that was slain
For the sins of the world, His blood breaks the chains
And every knee will bow before the Lion and the Lamb
Oh, every knee will bow before Him
[Bridge]
Who can stop the Lord Almighty?
For who can stop the Lord Almighty?
Who can stop the Lord Almighty?
Who can stop the Lord Almighty?
For who can stop the Lord Almighty?
Who can stop the Lord Almighty?
For who can stop the Lord Almighty?
Oh, who can stop the Lord, yeah?

[Chorus]
Our God is the Lion, the Lion of Judah
He’s roaring with power and fighting our battles
Every knee will bow before Him
Our God is the Lamb, the Lamb that was slain
For the sins of the world, His blood breaks the chains
And every knee will bow before the Lion and the Lamb
Oh, every knee will bow before Him
</plain_text_lyrics>

<formatted_lyrics>
<?xml version='1.0' encoding='UTF-8'?>
<song xmlns="http://openlyrics.info/namespace/2009/song" version="0.8" createdIn="OpenLP 3.1.7" modifiedIn="OpenLP 3.1.7" modifiedDate="2025-10-27T19:28:41">
  <properties>
    <titles>
      <title>Lion and the Lamb</title>
    </titles>
    <authors>
      <author>Leeland</author>
    </authors>
  </properties>
  <lyrics>
    <verse name="v1">
      <lines>He's coming on the clouds<br/>Kings and kingdoms will bow down<br/>And every chain will break<br/>As broken hearts declare His praise<br/>For who can stop the Lord Almighty?</lines>
    </verse>
    <verse name="c1">
      <lines>Our God is the Lion, the Lion of Judah<br/>He's roaring with power and fighting our battles<br/>And every knee will bow before Him<br/>Our God is the Lamb, the Lamb that was slain<br/>For the sin of the world, His blood breaks the chains<br/>And every knee will bow before the Lion and the Lamb<br/>Oh, every knee will bow before Him<br/></lines>
    </verse>
    <verse name="v2">
      <lines>Open up the gates<br/>Make way before the King of kings, oh, ooh-oh<br/>The God who comes to save<br/>Is here to set the captives free<br/>For who can stop the Lord Almighty?</lines>
    </verse>
    <verse name="c2">
      <lines>And our God is the Lion, the Lion of Judah<br/>He's roaring with power and fighting our battles<br/>And every knee will bow before Him<br/>And our God is the Lamb, the Lamb that was slain<br/>For the sin of the world, His blood breaks the chains<br/>And every knee will bow before the Lion and the Lamb<br/>Oh, every knee will bow before Him</lines>
    </verse>
    <verse name="b1">
      <lines>Who can stop the Lord Almighty?<br/>For who can stop the Lord Almighty?<br/>Who can stop the Lord Almighty?<br/>Who can stop the Lord Almighty?<br/><p style="page-break-after: always;"/><br/>For who can stop the Lord Almighty?<br/>Who can stop the Lord Almighty?<br/>For who can stop the Lord Almighty?<br/>Oh, who can stop the Lord? Yeah</lines>
    </verse>
    <verse name="c3">
      <lines>Our God is the Lion, the Lion of Judah<br/>He's roaring with power and fighting our battles<br/>And every knee will bow before Him<br/>Our God is a Lamb, the Lamb that was slain<br/>For the sin of the world, His blood breaks the chains<br/>And every knee will bow before the Lion and the Lamb<br/>Oh, every knee will bow before Him</lines>
    </verse>
    <verse name="e1">
      <lines>Oh, oh, oh<br/>And every knee will bow before the Lion and the Lamb<br/>Oh, oh, oh<br/>Oh, oh, oh, oh</lines>
    </verse>
  </lyrics>
</song>

</formatted_lyrics>


Convert:
<plain_text_lyrics>

</plain_text_lyrics>