+++
title = "Badger: Fast key-value database written in Go"

date = 2018-02-21T18:05:00
all_day = false

tags = ["Go Meetup", "Go"]

location = "San Francisco, California"

event = "GoSF Meetup"
event_url = "https://www.meetup.com/golangsf/events/245472050/"

abstract = """
Badger is a fast key-value database, written to provide a Go native alternative
to RocksDB. Typical LSM tree based KV DBs are fast in writes, but slower in
reads. Badger provides better write throughput than RocksDB while maintaining at
least the same level of read performance as B+-tree based stores like Bolt.
Badger achieves this remarkable feat by utilizing a new design which stores
values separately from keys, based on a paper called WiscKey. In this talk,
Manish will talk about the motivation to build Badger and the unique design
which makes this amazing read-write performance possible. He'll also talk about
how Go made it possible to build this DB with a high level of concurrency built
in, and with few engineering resources.

https://github.com/dgraph-io/badger

"""

url_slides = "http://bit.ly/2Cbw27X"
url_video = "https://www.youtube.com/watch?v=VftmLgwk_cY"

featured = true
+++
