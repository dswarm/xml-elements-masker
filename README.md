# xem - d:swarm XML elements masker

xem is a Scala program wrapped in a shell script. It takes the source files directory, the record tag, the mask elements and the target directory as input and masks the sub trees of the wanted XML elements in CDATA tags.

## Usage

```
xem
        --source-files-directory    [ABSOLUTE PATH TO SOURCE FILES DIRECTORY]
        --record-tag                [XML RECORD TAG]
        --mask-elements             [a comma-separated list of XML element tags, whose content and sub elements should be masked with CDATA]
        --target-files-directory    [ABSOLUTE PATH TO TARGET FILES DIRECTORY]
        --content-only              utilise only the content of the sub elements (i.e. without further XML elements tags inside)
        --help                       print this help
```

