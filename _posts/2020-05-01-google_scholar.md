---
layout: post
title: "Google Scholar Python to Check New Entries"

# keywords: Shamsee, Lone Idiot and Cub, Tristan J. Tarwater, Adrian Ricker
# description: Shamsee Lone Idiot and Cub - page 013

thumbnail: /images/posts/scholar.jpg

# facebook_type: 
# facebook_image: images/posts/catmen.jpg

---

## [ Google Scholar Python to Check New Entries](https://github.com/Ueur/Google_Scholar_Python_New_Entries)

<p><a href="https://github.com/Ueur/Google_Scholar_Python_New_Entries"><img src="/images/posts/scholar.jpg" alt="scholar" style="height: 50%; width: 50%;"/></a></p>


This project was created in the spring of 2020 for the Northwestern University Chemical Engineering newsletter, in order to obtain newly published articles every week from a list of professors. This would allow the department to add these new articles to the newsletter without pestering professors weekly.


## Prerequisite

```bash
pip install scholarly
```


## How to run

1. Install scholarly and have the researchers you want to track in "professor list" and their Google Scholar pages in "professor list url" file.
2. Run "google_scholar_panorama".
3. Articles not present from last time will be added to "new_add_result". It will also add them to "Search_History_File" if that file exists so that next time the code is run, it will not add them to "new_add_result". "search_history" is also kept to track the times the code was run.



## Notes

All professors are included in professor list except for:
- P. Daniels
- G. Holderfield
- B. Johnson
- M. Kulkarni
- S. Lichter
- M. Werwath

These professors' articles in Google Scholar do not link to their pages. This list can be modified as professors join or leave the department.

"Demo" shows a picture of the result of the code from deleting all previous entries of a particular professor and testing to see if running the code will add all her published articles again.

## License

[MIT](https://choosealicense.com/licenses/mit/)