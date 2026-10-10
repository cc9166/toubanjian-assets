# toubanjian-assets

Versioned illustration and signed content resources for Toubanjian. No application source code, user photos or API keys.

## Content updates

The app reads the signed `content/feed.json`. Sequence 4 provides names, countries, cities and introductions for all **101 landmarks in 20 languages**, including [Zhangjiajie · Wulingyuan](content/zhangjiajie/README.md). Display names and descriptions for all 17 templates are also localized.

Browse the [readable language files](content/localizations), for example [French](content/localizations/fr.json), [Japanese](content/localizations/ja.json) or [Arabic](content/localizations/ar.json). These are review copies; the app uses only the signed feed. Editing a review file alone does not publish a content update: regenerate and sign the feed from the source catalog.

Languages: `zh-Hans`, `zh-Hant`, `en`, `fr`, `es`, `de`, `pt-BR`, `it`, `ru`, `ja`, `ko`, `ar`, `hi`, `id`, `th`, `vi`, `tr`, `pl`, `nl`, `uk`.

The updated app displays and searches localized landmark information, caches it for offline use, and shares the same images across languages. Existing image URLs, layout versions and the 204 Chinese/English print editions are preserved. Printed artwork layouts still support Simplified Chinese and English independently of the interface language. Older app versions continue to use the bilingual fields.

Translations have automated source comparisons and selected editorial checks, but have not all undergone native-speaker review. Existing source references and image credits remain in place.
