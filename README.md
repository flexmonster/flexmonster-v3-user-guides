# Flexmonster user guide

This repo contains end-user documentation for the Flexmonster UI.

The pages are the same ones published in the [Flexmonster user guide](https://prerelease.flexmonster.com/user-guide/intro), converted to plain markdown so you can bring them into your own product's documentation.

You can use them in two ways:

- **Copy them as they are.** The pages are ready to use and work in any markdown-based docs tool.
- **Adapt them to your product.** Change the wording, remove the features you don't expose, and add your own screenshots and branding.

## What's inside

[`intro.md`](intro.md) is the landing page of the guide.

| Folder | Pages |
| --- | --- |
| [`configuring-fields/`](configuring-fields) | [Renaming field captions](configuring-fields/renaming-field-captions.md) |
| [`connecting-to-data/`](connecting-to-data) | [Connect to CSV data](connecting-to-data/connect-to-csv.md), [Connect to JSON data](connecting-to-data/connect-to-json.md) |
| [`data-shaping/`](data-shaping) | [Aggregation functions](data-shaping/aggregations.md), [Expanding the data](data-shaping/expanding-data.md), [Filtering by condition](data-shaping/filtering-by-condition.md), [Filtering by members](data-shaping/filtering-by-members.md), [How to choose fields to show](data-shaping/how-to-choose-fields-to-show.md), [Report filters](data-shaping/report-filters.md), [Sorting](data-shaping/sorting.md) |
| [`layouts-and-controls/`](layouts-and-controls) | [Field list](layouts-and-controls/field-list.md), [Filter view](layouts-and-controls/filter-view.md), [Grid layouts](layouts-and-controls/grid-layouts.md), [Toolbar](layouts-and-controls/toolbar.md) |
| [`saving-and-restoring/`](saving-and-restoring) | [Saving and restoring reports](saving-and-restoring/saving-and-restoring-reports.md) |
| [`assets/`](assets) | The images, videos, and icons the pages use |

## Getting started

1. Clone the repository, or download it as a ZIP:

   ```bash
   git clone https://github.com/flexmonster/flexmonster-v3-user-guides.git
   ```

2. Copy the pages, their folders, and the `assets/` folder into your documentation project. Keep the same structure: every image, video, and icon is linked with a relative path, so the pages work wherever you put them.

3. Add the pages to your docs tool's navigation.

The pages are standard markdown with no custom components. Each page starts with a front matter block:

```yaml
---
title: Sorting
permalink: /user-guide/sorting
---
```

If yours uses a different key for the URL, rename `permalink` or remove it.

## Staying up to date

This repository is synced automatically from the Flexmonster documentation. Each sync is a separate commit, which makes it easy to see what changed.

- If you copied the pages as they are, copy them again to pick up the updates.
- If you adapted the pages, compare the new commits against the version you started from (`git diff <old-commit> <new-commit>`) and apply the relevant changes to your copy by hand.

## Questions and feedback

If you find a mistake in the pages, or have a question about using them, contact [Flexmonster support](https://www.flexmonster.com/technical-support/).
