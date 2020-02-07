# Natalija Natein
Junior software developer.
## Contact Info
e-mail: [natein@gmail.com](mailto:natein@gmail.com)

skype: [natein](skype:natein)

## Summary
My goal is to work remotely for a company or to become a freelancer.
## Skills
C#/.NET

HTML/CSS/Javascript

Algorithms and data structures

## Code examples
Working with JSON data

	function businessNamesAndRatings(apiResult ) {
	    var len = apiResult.results.length;
	    var arr=[];
	    for (var i = 0; i < len; i++) {
	        var rating = apiResult.results[i].rating;
	        var name = apiResult.results[i].name;
	        arr.push({rating, name });
	    }
	    return arr;
	}

Automation InDesign excerpt

	Type type = Type.GetTypeFromProgID("InDesign.Application.CS5", true);
	dynamic app = System.Activator.CreateInstance(type, true);
	string docPath = @"C:\Works\Catalog.indd";
    	var doc = app.Open(docPath);
	var textFrame = doc.Pages.Item[1].TextFrames.Item["Code"];
    	textFrame.Contents = "Code: " + ProdId;
	textFrame = doc.Pages.Item[1].TextFrames.Item["Price"];
    	textFrame.Contents = "€ " + string.Format("{0:F2}", Price);

## Experience
[Personal Portfolio](https://codepen.io/natein/full/WrdBXm)

[Learning project Nerds](https://natein.github.io/Nerds/)

[Asia Holidays](https://codepen.io/natein/full/zoQyqe)

[Rio de Janeiro](https://codepen.io/natein/full/YpYYKY)


## Education
Omsk State University

[Stepik account](https://stepik.org/users/18193127/)
## English
I have pre-intermediate level. I can write simple sentenses and understand slow speech.
