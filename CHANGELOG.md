## Releases

--

#### 3.0.0 - 2022-03-28

⚠️ Breaking
* Our partner, Braze, has made a few significant changes to their web SDK.  As a result, we are also updating our mParticle Braze web kit to support Braze’s Web SDK version 3.5.0, which includes breaking changes to the Braze SDK behavior.  The updated mParticle Braze Web kit will be available via CDN on June 8, 2022 and is currently available on NPM at @mparticle/web-braze-kit v3.0.0.  Also note that we have updated the name of our npm package from @mparticle/web-appboy-kit to @mparticle/web-braze-kit.
* We highly recommend that you review the changes between version 2 and 3 of the Braze Web SDK to understand these changes, which can be found here.  To summarize:
  * The `appboy.ab` namespace has been removed and everything lives under the `appboy` namespace now.
  * `InAppMessage.Button` has been renamed to `InAppMessageButton`
* If you reference any of the above deprecations, you will have to make changes to your codebase before June 8, 2022 to be compatible with both version 2 and version 3 of the Braze SDK to ensure your code continues to work.
* Full details can be found in the README at our [AppBoy Repo](https://github.com/mparticle-integrations/mparticle-javascript-integration-appboy#readme).

#### 2.0.7 - 2022-02-09

-   Feat - add new Braze clusters

#### 2.0.6 - 2020-12-10

-   Feat - Add additional Braze clusters to URL mapping table

#### 2.0.5 - 2020-06-04

-   Update Braze to 2.5.2

#### 2.0.4 - 2020-02-12

-   Send SKU if forwardSkuAsProductName is set

#### 2.0.2 - 2020-01-23

-   Feat - Set event name sent to Braze as user provided pageName

#### 2.0.1 - 2019-12-03

-   Bugfix - Respect userId choice in mParticle UI dropdown
-   Add version number
-   Remove isObject dependency
