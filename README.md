## Fork of PHPWord for personal project

I needed to fix a bug with reading Word .doc files to continue my development.

### Changed

PhpWord\Reader\MsDoc.php line 144

```
$this->_DocumentSummaryInformation = $ole->getStream($ole->docSummaryInfos);
```

No support is given for this project. Please refer to [PHPWord](https://github.com/PHPOffice/PHPWord)
