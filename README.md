# h.b.c.u.-w.e.e.d
 """
# HBCU-WEED

This the rawest comedy spot alive. Ain’t no filters, no pandering, just pure Black energy. Sketches hit like your uncle wildin’ at the cookout. Truths cut like your grandma’s side eye. It’s smart, it’s stupid, it’s loud, it’s layered. If you ain’t laughin’, you ain’t listenin’. And if you soft, this ain’t for you.

## What It Is

HBCU-WEED is a real-time comedy network made for people who know what it feel like to grow up laughin’ through pain and cookin’ up genius from nothin’. It’s a sketch engine. A content archive. A space to create, submit, and wild out with your people. Everything you see is written with soul and served hot.

## How It Work

- Submit your sketch ideas straight through the site
- Get original content generated live by the sketch engine
- Watch and archive the wildest, smartest comedy online
- All numbers are real. All content is protected.

## This Ain’t No Gimmick

We don’t inflate views.
We don’t fake the feedback.
We don’t write for algorithms.
We write for us.

## Licensing

All rights reserved. You can’t copy, remix, repost, or resell anything on here without approval. 

HBCU-WEED is protected under a custom private license. Contact: madeintaiwansomehow@gmail.com
"""


df_files.loc[df_files['File'] == 'README.md', 'Content'] = final_readme_real
tools.display_dataframe_to_user(name="Final HBCU-WEED README", dataframe=df_files)
