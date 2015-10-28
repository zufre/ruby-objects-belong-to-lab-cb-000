
# Ruby Objects Belong To Lab

Song belongs to Artist
Song#name
Song#artist=
Song#artist
Song#artist_name # should not break on nil

Post belongs to Author
Post#name
Post#author=
Post#author
Post#author_name # should not break on nil

Really simple, attr_accessor basically makes it pass. delegate _name method makes sure they get the relationship
