---
title: Administrar la visualización de los nombres de los miembros en tu organización
intro: Puedes permitir que los miembros de tu organización vean un nombre de perfil del autor de un comentarios en los repositorios privados en la organización.
product: '{% data reusables.gated-features.display-names %}'
redirect_from:
  - /articles/managing-the-display-of-member-names-in-your-organization
  - /github/setting-up-and-managing-organizations-and-teams/managing-the-display-of-member-names-in-your-organization
versions:
  fpt: '*'
  ghes: '*'
  ghae: '*'
  ghec: '*'
topics:
  - Organizations
  - Teams
shortTitle: Administrar cómo se muestran los nombres de los miembros
---

Los propietarios de la organización pueden administrar la visualización de los nombres de los miembros en una organización.

![Nombre del perfil del autor del comentario que se muestra en un comentario](/assets/images/help/issues/commenter-full-name.png)

Cada miembro de la organización elige su propio nombre de perfil en sus configuraciones. Para obtener más información, consulta la sección "[Personalizar tu perfil](/github/setting-up-and-managing-your-github-profile/personalizing-your-profile#changing-your-profile-name)."

{% ifversion profile-name-enterprise-setting %}
Es posible que no puedas configurar este ajuste para tu organización si un propietario de la empresa configuró una política a nivel empresarial. Para obtener más información, consulta la sección "[Requerir políticas de administración de repositorios en tu empresa](/admin/policies/enforcing-policies-for-your-enterprise/enforcing-repository-management-policies-in-your-enterprise#enforcing-a-policy-for-inviting-outside-collaborators-to-repositories)".{% endif %}

{% data reusables.profile.access_org %}
{% data reusables.profile.org_settings %}
{% data reusables.organizations.member-privileges %}
5. Dentro de "Admin repository permissions" (Permisos del administrador del repositorio), selecciona o quita la marca de selección **Allow members to see comment author's profile name in private repositories (Permitir que los miembros vean el nombre de perfil del autor del comentario en los repositorios privados)**. ![Casilla de verificación para permitir que los miembros vean el nombre completo del autor del comentario en los repositorios privados](/assets/images/help/organizations/allow-members-to-view-full-names.png)
6. Haz clic en **Save ** (guardar).
