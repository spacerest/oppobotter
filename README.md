# oppobotter

methods:

choose_pic
- looks at pics that have been liked, not used, and checks that request to use hasn't been denied
	
get_keywords(pic_id)
- reads caption of chosen pic, gets some keywords after comparing that they exist in one of the syn/ant dictionaries)
  
get_antonyms([keyword1, keyword2])

choose_lyrics([antonym1, antonym2])

format_pic(pic_id, [lyric1, lyric2])
- puts lyrics on picture and saves
  
post_pic(pic_id, [lyric1, lyric2])
- tags the original poster (so that they still have the option to request a delete)
- adds a caption that includes: picture credit: @username, song #1: song name, artist name, song #2: song name, artist name

comment_liked_pics
- comment something like "<3 this cuz it's quite beautiful, hoping to repost via my account with a *kind of* random lyric, please reply "STOP" if you don't want me to and i'll take it out of queue. ~oppobotter"

data inputs needed:
- english synonym-antonym dictionary
- french synonym-antonym dictionary
- spanish synonym-antonym dictionary
- bunch of song lyrics (see https://gist.github.com/febuiles/1549991)
