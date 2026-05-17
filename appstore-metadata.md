# PATINA Store Metadata

Use this as the copy/paste source for App Store Connect and Google Play once
the accounts are ready.

## URLs

- Marketing URL: `https://gaborandi.github.io/patina-site/`
- Privacy Policy URL: `https://gaborandi.github.io/patina-site/privacy/`
- Support URL: `https://gaborandi.github.io/patina-site/support/`
- Terms URL: `https://gaborandi.github.io/patina-site/terms/`

The app Settings screen uses the same URLs from `src/config/ExternalLinks.ts`.

## iOS App Store

- App name: `Patina: Paint Time`
- Subtitle: `Cozy time-painting puzzle`
- Category: Games
- Subcategories: Puzzle, Casual
- Bundle ID: `com.patina.game`
- SKU suggestion: `patina-ios-001`

Promotional text:

```text
Tap objects to age them through time. Grow seeds, freeze water, weather stone, and restore hand-painted worlds in a quiet puzzle game about transformation.
```

Keywords:

```text
puzzle,cozy,zen,relaxing,time,paint,garden,restore,logic,casual,brain,offline,daily,art
```

Description:

```text
PATINA is a cozy puzzle game about painting with time.

Tap a seed and it begins to grow. Tap water and it freezes, drifts, and returns as rain. Tap stone and it remembers the shape of a temple. Every object moves forward through natural time states, and the best solutions trigger quiet chains of cause and effect.

There is no character to steer and no rushed timer. Each level is a small hand-painted board where one action matters: tap to age the world forward.

Solve compact tap-to-age puzzles, discover transformation cascades, restore forgotten gardens, collect mementos, and return for daily puzzles and seasonal scenes.

PATINA is designed to feel calm, tactile, and premium. Rewarded ads are optional, interstitial ads never interrupt active puzzle play, and purchases are focused on ad removal, visual themes, transformation effects, and garden decorations.

Tap once. Watch time arrive.
```

## Google Play

- App name: `Patina: Paint Time`
- Short description: `Tap objects through time and restore cozy hand-painted worlds.`
- Category: Game / Puzzle
- Tags: Puzzle, Casual, Offline, Stylized, Single player
- Contains ads: Yes
- In-app purchases: Yes
- Privacy policy: `https://gaborandi.github.io/patina-site/privacy/`

## IAP Product IDs

- `com.patina.game.remove_ads` - Remove Ads, non-consumable, $2.99
- `com.patina.game.founder` - Founder Pack, non-consumable, $4.99
- `com.patina.game.powerups_extra` - Power-Up Pack, consumable, $1.99
- `com.patina.game.theme_garden` - Golden Conservatory Theme, non-consumable, $1.99

Detailed pre-account release package:

- `docs/release/PRE_APPLE_ID_RELEASE_PACKAGE.md`
