# Streams
Streams are Node's control flow abstraction for handling data in time. As such they are a cornerstone of the event-driven, non-blocking I/O Node implements on top of v8.

Operations performed by streams are `reading`, `writing` and `transforming`. Node provides base classes for these purposes:

* Readable
* Writeable
* Duplex `Readable | Writable`
* Transform `Duplex`
* PassThrough `Duplex`


## See also

* [yoshuawuyts/knowledge/js/streams](https://github.com/yoshuawuyts/knowledge/blob/master/js/streams.md) - A pragmatic introduction with cues into extensions of the stream abstraction
* [substack/stream-handbook](https://github.com/substack/stream-handbook) - A complete guide to streams
* [chrisdickinson/streams](https://gist.github.com/chrisdickinson/0a236ce62097c806113d) - Notes about order and purpose of stream events
