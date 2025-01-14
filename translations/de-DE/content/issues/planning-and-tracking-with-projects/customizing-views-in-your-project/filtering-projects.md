---
title: 'Filtern von {% data variables.projects.projects_v2 %}n'
intro: 'Verwende Filter, um auszuwählen, welche Elemente in den Ansichten deines Projekts angezeigt werden sollen.'
miniTocMaxHeadingLevel: 3
versions:
  feature: projects-v2
redirect_from:
  - /issues/trying-out-the-new-projects-experience/filtering-projects
type: tutorial
topics:
  - Projects
allowTitleToDifferFromFilename: true
ms.openlocfilehash: b1c04738a3c03d892b360c3b23def694d202ee0c
ms.sourcegitcommit: f638d569cd4f0dd6d0fb967818267992c0499110
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/25/2022
ms.locfileid: '148108434'
---
Du kannst Ansichten mithilfe von Filtern für Elementmetadaten, z. B. zugewiesene Personen und die Bezeichnungen, die auf Issues angewendet werden, und über die Felder in deinem Projekt anpassen. Du kannst Filter kombinieren und als Ansichten speichern. Weitere Informationen findest du unter [Anpassen deiner Projektansichten](/issues/planning-and-tracking-with-projects/customizing-views-in-your-project/customizing-a-view).

Um ein Projekt zu filtern, klicke auf {% octicon "filter" aria-label="The Filter icon" %}, und gib die gewünschten Felder und Werte für den Filter ein. Während der Eingabe werden mögliche Werte angezeigt. Du kannst die Projektbefehlspalette auch öffnen, indem du {% data variables.projects.command-palette-shortcut %} drückst und „Filtern nach“ eingibst, um unter den verfügbaren Filtern eine Auswahl zu treffen.

Die Verwendung mehrerer Filter fungiert als logischer UND-Filter. Beispielsweise gibt `label:bug status:"In progress"` Elemente mit der Bezeichnung `bug` mit dem Status „In Bearbeitung“ zurück. {% data variables.product.prodname_projects_v2 %} unterstützt derzeit keine logischen ODER-Filter in mehreren Feldern.

Die gleichen Filter sind für Diagramme verfügbar, die du mithilfe von Erkenntnissen für {% data variables.product.prodname_projects_v2 %} erstellst, und ermöglichen das Filtern der zum Erstellen deiner Diagramme verwendeten Daten. Weitere Informationen findest du unter [Verwenden von Erkenntnissen mit Projekten](/issues/planning-and-tracking-with-projects/viewing-insights-from-your-project/about-insights-for-projects).

## Filtern von Elementen

Klicke oben in der Tabelle auf {% octicon "filter" aria-label="the filter icon" %}, um die Leiste zum Filtern nach Schlüsselwort oder Feld einzublenden. Beginne mit der Eingabe des Feldnamens und des Werts, nach dem du filtern möchtest. Während der Eingabe werden mögliche Werte angezeigt.

{% data reusables.projects.projects-filters %}

Alternativ drücke {% data variables.projects.command-palette-shortcut %}, um die Projektbefehlspalette zu öffnen, und beginne mit der Eingabe von „Filtern nach“.

Im Boardlayout kannst du auf Elementdaten klicken, um nach Elementen mit diesem Wert zu filtern. Klicke beispielsweise auf eine zugewiesene Person, um nur Elemente für diese Person anzuzeigen. Soll der Filter entfernt werden, klicke noch mal auf die Elementdaten.
