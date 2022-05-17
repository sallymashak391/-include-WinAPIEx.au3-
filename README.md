# -include-WinAPIEx.au3-
MsgBox(4096, '',  'My UniqueID: ' &amp; _WinAPI_UniqueHardwareID(BitOR($UHID_MB,  $UHID_BIOS, $UHID_HDD))) ; $UHID_MB is used regardless. _SDL_SetColorKey($pNewSurface, $_SDL_SRCCOLORKEY, 0) _SDL_BlitSurface($pOldBitmap, 0, $pNewSurface, 0) $hImage = _GDIPlus_ImageLoadFromFile($sFile)
