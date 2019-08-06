# SSRS Branding Resources

Branding in SSRS has been implemented really poorly and documented really poorly; however, the current state of branding is better than it has been.

Using branding packages we can replace the title text with an image and change a set of defined colours.

This repository has my tools to produce working, controllable, and presentable branding packages.

Included are a set of packages that deviate from the default branding in a number of useful ways.

Colours for the portal UI are defined in 5 sections:
    Primary
    Secondary
    Neutral Primary
    Neutral Secondary
    Neutral Tertiary

Each section has the following settings:
*    Master Colour (named after the section e.g primary, secondary)
*    Alt (named after the section with alt appended e.g. primaryAlt)
*    Alt2 (e.g. primaryAlt2)
*    Alt3 (e.g. primaryAlt3)
*    Alt4 (e.g. primaryAlt4 only occurs on Primary section)
*    Contrast (e.g. primaryContrast)

I have included packages that white out whole sections of definable colours to allow you to witness the effects of each setting in isolation.

I have used an easily recognisable spectrum of bright strong colours so you may easily identify each setting by the colour.

The colours are
*    Pink: Master colour
*    Cyan: Alt colour
*    Yellow: Alt2 colour
*    Blue: Alt3 colour
*    Red: Alt4 colour(the only applies to the primary colour block)
*    Green: Contrast colour

I have included a image of the spectrum.  Note that red is defined as #FF0000 and is not included normally as red is sometimes used in undefinable elements E.g. Settings Button Down.

The included packages are as follows:
*    UI All White.zip
           Use this to see which UI elements have undefinable colours.
*    UI All White Primary Spectrum.zip
           All UI colours are white except for the Primary Colour section, they are as above.
*    UI All White Secondary Spectrum.zip
           All UI colours are white except for the Secondary Colour section, they are as above. 
*    UI All White Neutral Primary Spectrum.zip
           All UI colours are white except for the neutralPrimary section, they are as above.
*    UI All White Neutral Secondary Spectrum.zip
           All UI colours are white except for the neutralSecondary section, they are as above.
*    UI All White Neutral Tertiary Spectrum.zip
           All UI colours are white except for the neutralTertiary section, they are as above.

For lack of a reasonable way to test them, I have ommited the KPI and report chart colour sections.