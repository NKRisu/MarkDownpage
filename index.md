## Exercise 1

### answers here:

#### text edit

Writing in Markdown is _not_ that hard!  
I **will** complete these lessons!  
"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"  
If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.

#### header

# Header one  
## Header two  
### Header three  
#### Header four  
##### Header five  
###### Header six  

#### links and reference

#### Colombian Symbolism in _One Hundred Years of Solitude_

[Search for it.](https://www.google.com)  

[You're **really, really** going to want to see this.](https://www.dailykitten.com)  

#### The Latest News from [the BBC](https://www.bbc.com/news)  

Do you want to [see something fun][a fun place]?  

Well, do I have [the website for you][another fun place]!  

[a fun place]: https://www.zombo.com  
[another fun place]: https://www.stumbleupon.com  

#### image and reference

![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)  

![Black cat][Black]  

![Orange cat][Orange]  

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg  
[Orange]: http://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png  

#### quotelines

I read this interesting quote the other day:

> "Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

> Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...

> His father told him that story: his father looked at him through a glass: he had a hairy face.

> He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

> He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!

#### lists

* Flour
* Cheese
* Tomatoes

1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour

* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)

* Calculus
  * A professor
  * Has no hair
  * Often wears green
* Castafiore
  * An opera singer
  * Has white hair
  * Is possibly mentally unwell

#### formatting text

1. Cut the cheese

    Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes
    
    Be careful when holding the knife.

    For more help on tomato slicing,
    see Thomas Jefferson's seminal essay _Tom Ate Those_.

#### paragraphs

We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.

#### soft break

1. Crack three eggs over a bowl.  
   Now, you're going to want to crack the eggs in such a way that you don't make a mess.  
   If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
   Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

## Exercise 2

#### GML, Generalized Markup Language
**GML** was developed in 1969 by Charles **G**oldfarb, Edward **M**osher and Raymond **L**orie, their surname initial were used to make up the term **GML**. Using GML, a document is marked up with tags that define what the text is, in terms of paragraphs, headers, lists, tables, and so forth.  
The document can then be automatically formatted for various devices simply by specifying a profile for the device. For example, it is possible to format a document for a laser printer or a line (_dot matrix_) printer or for a screen simply by specifying a profile for the device without changing the document itself.

#### Halibut
**Halibut** is a documentation production system, with elements similar to TeX, debiandoc-sgml, TeXinfo, and others. It is primarily targeted at people producing software manuals. Halibut reads documentation source in a single input format, and produces multiple output formats containing the same text.  
The supported output formats are:

* Plain ASCII text
* HTML
* PDF
* PostScript
* Unix man pages
* Unix info, generated directly as .info files rather than .texi sources
* Windows HTML Help (_.CHM files_), generated directly without needing a separate help compiler.
* Windows WinHelp (_old-style .HLP files_), also generated directly.

## Exercise 3

[Watch this video] (https://www.youtube.com/watch?v=H8ZH_mkfPUY)

![a dog.][dog]


[dog]: https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExaTNqem5ybW42ZHdreWR1amk3dHNnY29kdXJpY2YzdDJseDU3dWY3OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/gKHGnB1ml0moQdjhEJ/giphy.webp


## Exercise 4

```csharp
public class Person{
  private string name;
  private int age;

  public Person(string initialName)
  {
    this.age = 0;
    this.name = initialName;
  }
  public void PrintPerson()
  {
    Console.WriteLine(this.name + ", age " + this.age + " years");
  }
  public void GrowOlder()
  {
    this.age = this.age + 1;
  }
}
