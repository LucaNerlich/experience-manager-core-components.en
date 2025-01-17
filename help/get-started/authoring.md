---
title: Authoring with Core Components
description: In AEM, components are the structural elements that constitute the content of the pages being authored - Core Components offer flexible and feature-rich authoring functionality.
role: Architect, Developer, Admin, User
exl-id: 56e58303-a178-45ab-b59d-e374c9cf90cf
---
# Author with Core Components

In Adobe Experience Manager, components are the structural elements that constitute the content of the pages being authored.

The Core Components offer flexible and feature-rich authoring functionality. The [WKND reference site](https://wknd.site) and its illustrates how the core components can be used to implement a rich website experience.

To experience the Core Components and see examples of their configuration options as well as HTML and JSON output, visit the [Component Library](https://adobe.com/go/aem_cmp_library).

For a more in-depth, developer-oriented introduction to implementing the Core Components on an AEM project by using the [AEM Project Archetype](/help/developing/archetype/overview.md) check out [the WKND tutorial.](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html)

>[!NOTE]
>
>Core Components are not immediately available to authors, the [development team must first integrate them to your environment](/help/get-started/using.md). Once integrated, they may be made available and pre-configured via the [template editor](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/templates.html).

>[!CAUTION]
>
>Core Components [require AEM 6.4 or higher](/help/versions.md) and require the use of [editable templates](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/templates.html). They do not work with the Classic UI nor with static templates.

## Authoring with Core Components {#authoring-with-core-components}

As an author, you will notice several advantages of the Core Components, including:

* Simple to use and well-integrated with the [page editor](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/editing-content.html)

* Feature-rich capabilities to accommodate many use cases as illustrated by the [WKND reference site](https://wknd.site) as well as in the [Component Library](https://adobe.com/go/aem_cmp_library)

* [Pre-configurable](#pre-configuring-core-components) to define which features are available to page authors via the [template editor](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/templates.html)

* Built around [accessibility guidelines](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/accessible-content.html)  

* Built to support [responsive layout](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/responsive-layout.html)

* Built to support [easy localization](localization.md)

Components are available on the **Components** tab of the side panel of the page editor when [editing a page](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/editing-content.html).

Components are grouped according to categories called component groups to easily organize and filter the components. The component group name is displayed with the component in the [component browser](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/fundamentals/editing-content.html) and it is also possible to filter by group to easily find the right component.

>[!NOTE]
>
>The Core Components are by default part of a hidden group and are not visible within the component browser.
>
>Add the required components to a visible group or customize them for them to be available for authors.

## Pre-Configuring Core Components {#pre-configuring-core-components}

Configuring Foundation Components was the job of a developer. However with Core Components, a template author can now configure a number of capabilities via the template editor.

For example if an image component should not allow image upload from the file system, or if a text component should only allow certain paragraph formatting, these features can be enabled or disabled with a simple click.

See [Creating Page Templates](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/templates.html) for more information.

### Edit and Design Dialogs {#edit-and-design-dialogs}

Because the Core Components can be pre-configured by template authors to define what options are allowed as part of a template, and then further configured by the page author to define actual page content, each component can have options in two different dialogs.

||Description|What it Controls|Examples|
|--- |--- |--- |--- |
|**Edit Dialog**|Options that a **page author** can modify during normal page editing for the placed components|The content displayed by the component and how it will ultimately appear on the page.|Formatting of content text, rotate an image on a page|
|**Design Dialog**|Options that a **template author** can modify when configuring a page template.|What options the page author has available when editing the component|Which text formatting options are available, which image in-place options are available|

### Component Styling {#component-styling}

The styles of most Core Components can be defined using the AEM style system.

* A template author can define which styles are available for a particular component in the Design Dialog of that component.
* The content author can then choose which styles to apply when adding the component and creating content.

For further details see the [Style System](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/sites/authoring/features/style-system.html) documentation.

## Developer Resources {#developer-resources}

See the [Developing Core Components](/help/developing/overview.md) developer documentation for technical information regarding core components.
