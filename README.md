# Task1

I need to build a button using these commands:
document.createElement("[haluttu_HTML-tag]");
[lisättävän_elementin_nimi].setAttribute("[attribuutti]", "[attribuutin_arvo]")
document.[elementti_johon_lisätään].appendChild([lisättävän_elementin_nimi])



There is a btton in HTML document that calls function addButton(). Function has to create new button element and add it to the boddy element.
When you press the element, it should call Hello() function.



I have tried following code but does not work.
I am using Viope study platform so it is quite clumsy.

	 var btn = document.createElement('button');
    btn.addEventListener('click', function(){
     alert('testing');
    });

    document.getElementByTagName('body')[0].append(btn);

	
