**Partner Centre Learning Path** is a selection of topics related to the Partner Centre: [Mastering the Partner Centre](https://microsoft.github.io/Mastering-the-Marketplace/partner-center/); here you can learn more about deal sharing and IP Cosell activities, among other topics.

Links to our solution catalogues - **AppSource** (audience: business folks) and **Marketplace** (tech folks):

[AppSource (business apps)](https://appsource.microsoft.com/en-us/)

[Marketplace (cloud software)](https://azuremarketplace.microsoft.com/en-US/)

Great place to start exploring all topics around Azure Marketplace (and VMs, SaaS + Azure Managed Apps specifically) is the [Mastering the Marketplace](https://microsoft.github.io/Mastering-the-Marketplace/) docs hub.

After that, you can jump right into the publishing process with [working with VM offers](https://microsoft.github.io/Mastering-the-Marketplace/vm/), [working with Azure Managed Applications](https://microsoft.github.io/Mastering-the-Marketplace/ama/) or [working with SaaS offers](https://microsoft.github.io/Mastering-the-Marketplace/partner-center/saas/) docs section; it takes you to a list of articles and videos, which explain the publishing process for transactable offers in Partner Centre. For SaaS solutions, [Mastering the SaaS accelerator](https://microsoft.github.io/Mastering-the-Marketplace/saas-accelerator/) contains everything you need to deploy the SaaS landing page + lifecycle API into Azure (needed only for SaaS, for Managed Apps there is an optional webhook which can be reused from this repo). After that, [here](https://microsoft.github.io/Mastering-the-Marketplace/ama/#managed-applications-overview) you can see how private offers work and what’s the difference between private offers and private [subscription] plans.

Important is to review [how the whole purchase process looks like from the both publisher’s and customer’s perspective](https://microsoft.github.io/Mastering-the-Marketplace/partner-center/private-offers/).

---
Links into our docs; as they are reviewed during a Marketplace onboarding session:

-   Docs for Azure Marketplace: [Welcome to the commercial marketplace | Microsoft Docs](https://docs.microsoft.com/en-us/azure/marketplace/)
-   Here you can see what is transactable and what not (or to put it differently, what can Microsoft invoice to your end-customers and what not): [Microsoft commercial marketplace transact capabilities | Microsoft Docs](https://docs.microsoft.com/en-us/azure/marketplace/marketplace-commercial-transaction-capabilities-and-considerations)
-   Overview of Marketplace offer types, we discussed VMs, SaaS and Azure Managed Application in depth - [Publishing guide by offer type - Microsoft commercial marketplace | Microsoft Docs](https://docs.microsoft.com/en-us/azure/marketplace/publisher-guide-by-offer-type)
-   **Virtual Machines** offering type details: [Plan a virtual machine offer - Microsoft commercial marketplace | Microsoft Learn](https://learn.microsoft.com/en-us/partner-center/marketplace-offers/marketplace-virtual-machines)

	-   Plans and pricing options: [Configure pricing and availability for a virtual machine offer in Partner Center | Microsoft Learn](https://learn.microsoft.com/en-us/partner-center/marketplace-offers/azure-vm-plan-pricing-and-availability#pricing)

-   **SaaS** offering type details: [Plan a SaaS offer for Marketplace or AppSource | Microsoft Docs](https://docs.microsoft.com/en-us/azure/marketplace/plan-saas-offer); there you can also see a description of each field of the offer, people publishing offers on Marketplace usually find it helpful to have this page open, while creating the offer

	-   SaaS Application Lifecycle [Managing the SaaS subscription life cycle | Microsoft Docs](https://docs.microsoft.com/en-us/azure/marketplace/partner-center-portal/pc-saas-fulfillment-life-cycle)
	-   SaaS Billing API example, Onboarding / Landing Page Implementation examples to be found here: [GitHub - Azure/Commercial-Marketplace-SaaS-Accelerator: A reference example with sample code for developers interested publishing transactable, Software as a-Service offers in the Microsoft commercial marketplace.](https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator)

		-   To deploy the technical artifacts and get information needed for the listing, follow installation instructions [here](https://github.com/Azure/Commercial-Marketplace-SaaS-Accelerator?tab=readme-ov-file#installation)

	-   SaaS Pricing is usually a topic for a longer discussion; with SaaS we have two options (more details about creating subscription plans here: [Create plans for a SaaS offer in Azure Marketplace](https://learn.microsoft.com/en-us/partner-center/marketplace/create-new-saas-offer-plans)

		-   Per user pricing
		-   Fixed price (per month, year, 2 years, 3 years)
			-   Alternatively, with custom pricing dimensions (onboarding, data_processed_overage, data_capacity, emails_sent etc)

	-   The technical part (deploying the landing page + webhook) – this is the easy part. Most of the time is usually spent on discussing how an ISV is going to construct their prices (public vs private, fixed prices with dynamics pricing options or not, having one offering with various options activated via “custom metering dimensions” vs having “multiple product offers bundled into one private offer” etc.

-   **Azure Managed Application** offering type details: [Plan an Azure managed application for an Azure application offer | Microsoft Learn](https://learn.microsoft.com/en-us/partner-center/marketplace-offers/plan-azure-app-managed-app)

	-   Azure Managed Application lifecycle events: [Capturing lifecycle events from your Azure Managed Application deployments - Microsoft Community Hub](https://techcommunity.microsoft.com/t5/apps-on-azure-blog/capturing-lifecycle-events-from-your-azure-managed-application/ba-p/3902995)

-   **Private offers** – Private offers can be used to bundle multiple Marketplace offerings into one, customer specific bundle/package, provide customer specific pricing, discounts etc

---
For SaaS applications, these runs in your own tenant + subscription, and later, PRACR (Partner Recognized Azure Revenue) may be a great way to make the consumption per customer visible to Microsoft – here is how to do that:

-   [Partner-reported Azure consumed revenue - Partner Center | Microsoft Learn](https://learn.microsoft.com/en-us/partner-center/referrals/partner-reported-azure-consumed-revenue)

Overview of IP Cosell top-tier benefits

-   [Azure IP co-sell top-tier benefits - Partner Center | Microsoft Learn](https://learn.microsoft.com/en-us/partner-center/referrals/azure-ip-co-sell-top-tier-benefits)
