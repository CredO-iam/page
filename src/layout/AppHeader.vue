<template>
    <header class="header-global">
        <base-nav class="navbar-main" transparent type="" effect="light" expand>
            <router-link slot="brand" class="navbar-brand mr-lg-5" to="/">
              <svg class="brand-logo" xmlns="http://www.w3.org/2000/svg" xml:space="preserve" viewBox="0 2100 15000 3500">
                  <defs>
                    <linearGradient id="fade">
                      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0" />
                      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="1" />
                    </linearGradient>
                  </defs>
                <path fill="url(#fade)" d="M7479 3677v-355l-830 781h359l470-426zm0 849-470-424h-359l830 783v-359z" />
                <path fill="#FFFFFF" d="M8671 3677v-355l830 781h-359l-470-426zm0 849 470-424h359l-830 783v-359zm-354-628-368 635 72 139c7 15 14 25 23 32q13.5 9 33 9c11 0 23-3 33-11 11-7 19-17 25-30l228-449c7-15 14-33 18-55 5-22 8-44 8-65 0-20-3-42-8-64s-11-41-18-55zm-185-363c-7-15-14-25-23-32q-13.5-9-33-9c-11 0-23 4-33 11-11 8-19 17-25 29l-229 451c-8 15-14 33-18 55-5 22-7 43-7 63 0 22 3 45 8 67s11 39 17 52l46 87 368-635zm449-87-136 230 112 217c14 28 25 61 33 97 8 37 12 74 12 110 0 39-4 77-12 113q-12 54-33 96l-221 435c-35 65-72 112-111 139-40 28-89 41-148 41-60 0-110-14-151-43q-61.5-43.5-108-135l-61 114c-11 19-26 35-43 46s-36 17-56 17c-30 0-56-10-76-30s-30-46-30-76c0-10 2-20 5-32 3-11 8-22 15-31l135-229-109-216c-15-29-26-61-34-97q-12-54-12-111t12-111c8-36 19-68 34-96l221-435c34-65 71-112 110-139 39-28 89-41 149-41 61 0 111 14 152 42s76 72 105 133l64-114c11-20 25-35 41-45 17-11 36-16 58-16q43.5 0 75 30c21 20 32 46 32 76q0 13.5-6 30c-4 11-9 21-16 31z" />
                <path fill="#FFFFFF" d="M1463 4843c-66 0-124-16-172-48s-90-83-125-153l-221-439c-13-25-23-53-29-83s-9-62-9-97q0-54 9-102c6-31 16-60 29-84l221-439c33-69 74-119 123-152s107-49 174-49h377c36 0 64 10 86 30s33 46 33 77c0 30-11 56-33 76s-51 30-86 30h-377c-21 0-40 6-58 17s-33 28-44 48l-218 443c-7 15-11 31-15 47-3 17-5 34-5 53 0 20 2 38 5 55s8 33 15 47l218 440c11 21 25 37 44 50 18 12 38 19 58 19h377c36 0 64 10 86 30s33 46 33 77-11 57-33 77-51 30-86 30zm1228-1081v112l177-155c26-23 58-41 95-55 37-13 73-20 108-20h140c87 0 161 31 224 93 62 62 94 136 94 222v49c0 36-10 64-30 86s-46 33-77 33-57-11-77-33-30-51-30-86v-49c0-27-10-51-31-72s-45-32-73-32h-140c-11 0-25 3-40 9s-27 14-36 22l-305 269v569c0 36-10 64-30 86s-46 33-77 33-57-11-77-33-30-51-30-86v-962c0-36 10-65 29-86s45-32 77-32c31 0 57 11 77 33s30 50 30 85zm1766 93c-11 0-22 2-33 7s-22 11-34 19l-91 75c-12 9-21 21-28 36-7 14-11 29-11 44v144h625v-144c0-15-3-30-11-44-7-14-16-26-27-34l-93-77c-11-8-22-15-33-19-11-5-22-7-33-7h-233zm-3-211h235c36 0 71 6 106 19s67 31 97 55l91 73c35 29 63 65 83 109 21 44 31 89 31 135v254c0 30-11 56-33 76s-51 30-86 30h-719v56c0 15 3 30 11 44 7 14 16 26 28 35l91 77c10 8 20 13 30 17 11 4 23 6 37 6h523c36 0 64 10 86 30s33 46 33 77-11 57-33 77-51 30-86 30h-526c-36 0-70-6-104-19-34-12-66-30-97-55l-91-77q-54-43.5-84-108c-20-43-30-87-30-133v-416q0-69 30-135c20-44 48-80 84-109l91-73c31-25 63-44 97-56s69-19 104-19zm1552 213c-22 0-45 9-69 28-2 1-3 2-4 3l-71 56c-9 7-17 18-22 31-6 13-8 27-8 40v455c0 14 3 28 8 42 6 14 14 24 22 31l71 56 3 3c25 19 48 28 71 28h165c13 0 25-3 37-8s25-13 38-23l180-146c8-6 15-17 20-31 6-14 8-28 8-43v-272c0-15-3-29-8-43-6-14-12-24-20-30l-180-145c-12-11-25-19-36-23-11-5-24-8-39-8h-165zm663-541v1408c0 35-10 63-31 86q-31.5 33-78 33c-32 0-58-11-77-32-19-22-29-50-29-87v-24l-79 69c-27 23-58 41-94 54s-72 19-110 19h-165c-36 0-72-6-106-19-35-12-67-30-97-55l-73-56c-35-27-63-63-83-107-21-44-31-90-31-137v-462q0-61.5 33-129c22-45 49-80 81-104l73-56c31-25 64-44 97-56 34-12 69-19 106-19h165c37 0 74 7 110 20s67 31 94 55l79 68v-470c0-35 10-64 30-86s46-33 77-33 58 11 78 33c21 22 31 50 31 86z" />
                </svg>
            </router-link>
            <ul class="navbar-nav align-items-lg-center ml-lg-auto">
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://www.linkedin.com/company/cred0/about" target="_blank" rel="noopener"
                       data-toggle="tooltip" title="Follow us on Twitter">
                        <i class="fa-brands fa-linkedin"></i>
                        <span class="nav-link-inner--text d-lg-none">Twitter</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://github.com/CredO-iam"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Star us on Github">
                        <i class="fa-brands fa-github"></i>
                        <span class="nav-link-inner--text d-lg-none">Github</span>
                    </a>
                </li>
                <li class="nav-item">
                    <a class="nav-link nav-link-icon" href="https://github.com/CredO-iam"
                       target="_blank" rel="noopener" data-toggle="tooltip" title="Star us on Github">
                        <i class="fa-brands fa-bluesky"></i>
                        <span class="nav-link-inner--text d-lg-none">Github</span>
                    </a>
                </li>
                <li class="nav-item d-none d-lg-block ml-lg-4">
                    <a href="https://demo.cred0.org/saas" target="_blank" rel="noopener"
                       class="btn btn-neutral btn-icon">
                <span class="btn-inner--icon">
                  <i class="fa fa-get-pocket mr-2"></i>
                </span>
                        <span class="nav-link-inner--text">DEMO</span>
                    </a>
                </li>
            </ul>
        </base-nav>
    </header>
</template>
<script>
import BaseNav from "@/components/BaseNav";
import BaseDropdown from "@/components/BaseDropdown";
import CloseButton from "@/components/CloseButton";

export default {
  components: {
    BaseNav,
    CloseButton,
    BaseDropdown
  }
};
</script>
<style>
.brand-logo {
  height: 70px;
  transition: height 0.3s ease;
}

@media (max-width: 768px) {
  .brand-logo {
    height: 50px;
  }
}

@media (max-width: 480px) {
  .brand-logo {
    height: 40px;
  }
}

@media (min-width: 769px) and (max-width: 1024px) {
  .brand-logo {
    height: 60px;
  }
}
</style>
