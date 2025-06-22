# Unicode-rbx
Unicode library for Roblox

**API:**
```


Unicode.sub(str, startIndex, endIndex)
Unicode.contains(inputValue, patternValue)

Unicode.lower(str)
Unicode.upper(str)

Unicode.codes(str)

Unicode.getBlock(codepoint)

Unicode.filter(str, filter)
Unicode.filterWithBlockWhitelist(str, filter)
Unicode.filterWithBlockAllowlist(str, filter)
Unicode.filterWithBlockBlacklist(str, filter)
Unicode.filterWithBlockDenylist(str, filter)

Unicode.check(str, filter)
Unicode.checkWithBlockWhitelist(str, filter)
Unicode.checkWithBlockAllowlist(str, filter)
Unicode.checkWithBlockBlacklist(str, filter)
Unicode.checkWithBlockDenylist(str, filter)

Unicode.isUnsupportedCodepoint(codepoint, font)
Unicode.containsUnsupportedCodepoint(str, font)

Unicode.findConfusable(codepoint)
Unicode.normalizeConfusables(str)
Unicode.findNormalizable(codepoint)
Unicode.normalize(str)

Unicode.isNonCharacterCodepoint(codepoint)
Unicode.containsNonCharacter(str)

Unicode.isZeroWidthCharacterCodepoint(codepoint)
Unicode.containsZeroWidthCharacter(str)

Unicode.isSpecialAreaCodepoint(codepoint)
Unicode.containsSpecialAreaCharacter(str)

Unicode.isEmojiSequence(codepoints)
Unicode.containsEmoji(str)
Unicode.isEmoji(str)

Unicode.isNonScriptCharacter(codepoint)
Unicode.containsNonScriptCharacter(str)
Unicode.filterNonScriptCharacters(str)

Unicode.BasicSymbolsBlocklist { string }

Unicode.pass(str, font, { Unsupported, NonCharacter, ZeroWidth, NonScript, SpecialArea }, blocklist, filter)

For Unicode 16.0.0
```
