# nessmediametadataretriever

<h1 align='center'><a href='https://github.com/nessblo/nessmediametadataretriever'>nessmediametadataretriever</a></h1>
<h4 align='center'>A Flutter plugin to read metadata of media files for Android and IOS.</h4>
<h5 align='center'>A part of <a href='https://github.com/nessblo'>Ness</a> open source project 💜</h5>
<br></br>

## Install

Add in your `pubspec.yaml`.

```yaml
dependencies:
  ...
  nessmediametadataretriever: ^1.0.0
```

Issues are maintained [here](https://github.com/nessblo).

## Support


## Example

```dart
var metadata = await NessMetadataRetriever.fromFile(File('your file path'))

String? trackName = metadata.trackName;
List<String>? trackArtistNames = metadata.trackArtistNames;
String? albumName = metadata.albumName;
String? albumArtistName = metadata.albumArtistName;
int? trackNumber = metadata.trackNumber;
int? albumLength = metadata.albumLength;
int? year = metadata.year;
String? genre = metadata.genre;
String? authorName = metadata.authorName;
String? writerName = metadata.writerName;
int? discNumber = metadata.discNumber;
String? mimeType = metadata.mimeType;
int? trackDuration = metadata.trackDuration;
int? bitrate = metadata.bitrate;
Uint8List? albumArt = metadata.albumArt;
```

## Platforms

|Platform|Status     |
|--------|-----------|
|Android |Working    |
|IOS   |Working    |


## License

This library & work under this repository is MIT licensed.

Copyright (C) 2021 Abdoulaye M Koné <abdoulaye.m.kone@gmail.com>
