---
title: Informationen zu „Enterprise“ (Unternehmens)-Konten
intro: 'Mit {% data variables.product.prodname_ghe_cloud %} können Sie ein Enterprise Konto erstellen, um die Zusammenarbeit zwischen Ihren Organisationen zu ermöglichen und gleichzeitig den Administratoren einen zentralen Anlaufpunkt für Transparenz und Verwaltung zu bieten.'
product: '{% data reusables.gated-features.enterprise-accounts %}'
redirect_from:
  - /articles/about-github-business-accounts/
  - /articles/about-enterprise-accounts
versions:
  free-pro-team: '*'
  enterprise-server: '*'
---

### Informationen zu „Enterprise“ (Unternehmens)-Konten

Mit einem Unternehmens-Konto kannst Du mehrere {% data variables.product.prodname_dotcom %}-Organisationen und {% data variables.product.prodname_ghe_server %}-Instanzen verwalten. Ihr Enterprise-Konto benötigt einen Handle, beispielsweise eine Organisation oder ein persönliches Konto auf {% data variables.product.prodname_dotcom %}. Enterprise-Administratoren können Einstellungen und Voreinstellungen verwalten, darunter folgende:

- Mitgliederzugang und -verwaltung (Organisationsmitglieder, externe Mitarbeiter)
- Abrechnung und Nutzung ({% data variables.product.prodname_ghe_server %}-Instanzen, Benutzerlizenzen, {% data variables.large_files.product_name_short %}-Pakete)
- Sicherheit (Single-Sign-On, Zwei-Faktor-Authentifizierung)
- Anfragen und Unterstützen von Bundle-Sharing mit {% data variables.contact.enterprise_support %}

{% data reusables.enterprise-accounts.enterprise-accounts-billing %}

Weitere Informationen über die Unterschiede zwischen {% data variables.product.prodname_ghe_cloud %} und {% data variables.product.prodname_ghe_server %} findest Du auf „[Produkte von {% data variables.product.prodname_dotcom %}](/articles/githubs-products)." Um auf {% data variables.product.prodname_enterprise %} zu hochzustufen oder um mit einem Unternehmenskonto einzusteigen, kontaktiere bitte {% data variables.contact.contact_enterprise_sales %}.

Weitere Informationen zu Mitgliederzugang und -verwaltung findest Du unter „[Benutzer in Deinem Enterprise-Konto verwalten](/articles/managing-users-in-your-enterprise-account).“

For more information about managing enterprise accounts using the GraphQL API, see "[Enterprise accounts](/v4/guides/managing-enterprise-accounts)."

### Mit Deinem Enterprise-Konto verknüpfte Organisationen verwalten

Organisationen sind gemeinsame Konten, in denen Personengruppen projektübergreifend zusammenarbeiten können. Inhaber können den Mitgliederzugang zu den Daten und Projekten der Organisation mit komplexen Sicherheits- und Administrationsfunktionen verwalten. Weitere Informationen finden Sie unter „[Informationen zu Organisationen](/articles/about-organizations)“.

Enterprise-Inhaber können Organisationen erstellen und mit dem Enterprise-Konto verknüpfen. Nachdem Du Organisationen zu Deinem Enterprise-Konto hinzugefügt hast, kannst Du die Richtlinien der Organisationen verwalten und erzwingen. Die spezifischen Optionen für das Erzwingen variieren je nach Einstellung. Im Allgemeinen können Sie wählen, ob Sie eine einzige Richtlinie für alle Organisationen in Ihrem Enterprise-Konto erzwingen oder es den Inhabern ermöglichen möchten, Richtlinien auf Organisationsebene festzulegen.

Weitere Informationen finden Sie unter „[Organisationen in Ihrem Enterprise-Konto verwalten](/articles/managing-organizations-in-your-enterprise-account)“ und „[Richtlinien für Organisationen in Ihrem Enterprise-Konto festlegen](/articles/setting-policies-for-organizations-in-your-enterprise-account)“.

### {% data variables.product.prodname_ghe_server %}-Lizenzen verwalten, die mit Deinem Unternehmens-Konto verknüpft sind

{% data reusables.enterprise-accounts.admin-managing-licenses %}
