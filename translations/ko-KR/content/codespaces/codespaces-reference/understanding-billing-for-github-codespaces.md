---
title: GitHub Codespaces 청구 이해하기
intro: '{% data variables.product.prodname_github_codespaces %} 사용량에 대한 요금이 청구되는 방법을 알아봅니다.'
versions:
  fpt: '*'
  ghec: '*'
redirect_from:
- /github/developing-online-with-codespaces/about-billing-for-codespaces
- /codespaces/getting-started-with-codespaces/about-billing-for-codespaces
- /codespaces/codespaces-reference/about-billing-for-codespaces
- /codespaces/codespaces-reference/understanding-billing-for-codespaces
type: reference
topics:
- Codespaces
- Billing
product: '{% data reusables.gated-features.codespaces %}'
shortTitle: Understanding billing
ms.openlocfilehash: 2dfec9e452360db117bdee7954fbe4fad2ad1c56
ms.sourcegitcommit: 47bd0e48c7dba1dde49baff60bc1eddc91ab10c5
ms.translationtype: HT
ms.contentlocale: ko-KR
ms.lasthandoff: 09/05/2022
ms.locfileid: "147111686"
---
이 문서에서는 codespace 요금 청구 방식과 조직의 청구 관리자가 어떻게 도움이 되는지 설명합니다.

## {% data variables.product.prodname_github_codespaces %} 액세스 권한 얻기

조직 관리자는 {% data variables.product.prodname_github_codespaces %} 사용을 특정 개인 계정으로만 제한할 수 있습니다. 액세스 권한을 얻으려면 청구 관리자에게 문의해야 합니다. 자세한 내용은 “[codespace 액세스 및 보안 관리](/codespaces/managing-your-codespaces/managing-access-and-security-for-your-codespaces)”를 참조하세요.

## {% data variables.product.prodname_codespaces %}를 사용하는 데 드는 비용

{% data variables.product.prodname_codespaces %} 사용 요금을 보려면 “[{% data variables.product.prodname_codespaces %} 가격 책정](/billing/managing-billing-for-github-codespaces/about-billing-for-codespaces#codespaces-pricing)”을 참조하세요.

## codespace 사용 요금 청구 방식

codespace는 컴퓨팅 시간(분)과 디스크에서 사용하는 스토리지 양에 대한 요금이 청구됩니다.

codespace 사전 빌드를 사용하도록 설정하면 추가 요금이 발생합니다. 자세한 내용은 “[{% data variables.product.prodname_github_codespaces %} 사전 빌드 정보](/codespaces/prebuilding-your-codespaces/about-github-codespaces-prebuilds#about-billing-for-codespaces-prebuilds)”를 참조하세요.

### 컴퓨팅 시간(분) 이해
codespace는 활성화된 시간(분)에 대한 요금이 청구됩니다. codespace 창이 30분 동안 유휴 상태로 유지되면 자동으로 종료되고, codespace를 다시 시작할 때까지 codespace에 대한 컴퓨팅 청구가 종료됩니다.

### codespace 스토리지 요금 청구 방식 이해
{% data variables.product.prodname_github_codespaces %}에서 스토리지는 복제된 리포지토리, 구성 파일, 확장 등 Codespace와 관련된 모든 파일을 포함하는 것으로 정의됩니다. 스토리지 요금은 codespace가 종료된 동안에도 청구됩니다. codespace에 대한 스토리지 청구는 https://github.com/codespaces 에서 수동으로 삭제할 때 종료됩니다.

## 지출 한도 작동 방식

조직에서 {% data variables.product.prodname_codespaces %}를 사용하려면 먼저 청구 관리자가 지출 한도를 설정해야 합니다. 자세한 내용은 “[{% data variables.product.prodname_github_codespaces %}에 대한 지출 한도 관리](/billing/managing-billing-for-github-codespaces/managing-spending-limits-for-github-codespaces)”를 참조하세요. 

## 지출 한도에 도달한 경우 변경 내용 내보내기

{% data reusables.codespaces.exporting-changes %}

## 현재 사용량 및 한도 확인
현재 사용량 또는 지출 한도를 확인해야 하는 경우 조직의 청구 관리자에게 문의하세요. 자세한 내용은 “[{% data variables.product.prodname_github_codespaces %} 사용량 보기](/billing/managing-billing-for-github-codespaces/viewing-your-github-codespaces-usage)”를 참조하세요.

## codespace 자동 삭제 가능

조직 또는 리포지토리에서 제거된 사용자의 codespace는 자동으로 삭제됩니다.

## 사용되지 않는 codespace 삭제

https://github.com/codespaces 및 {% data variables.product.prodname_vscode %} 내에서 codespace를 수동으로 삭제할 수 있습니다. codespace의 크기를 줄이려면 터미널을 사용하거나 {% data variables.product.prodname_vscode %} 내에서 파일을 수동으로 삭제할 수 있습니다.

## 추가 참고 자료

- [조직의 {% data variables.product.prodname_github_codespaces %}에 대한 청구 관리](/codespaces/managing-codespaces-for-your-organization/managing-billing-for-github-codespaces-in-your-organization)