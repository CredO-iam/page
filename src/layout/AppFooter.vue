<template>
    <footer class="footer has-cards">
        <div class="container">
            <div class="row row-grid align-items-center my-md">
                <div class="col-lg-6">
                    <h3 class="text-primary font-weight-light mb-2">Thank you for supporting us!</h3>
                    <h4 class="mb-0 font-weight-light">Let's get in touch on any of these platforms.</h4>
                </div>
                <div class="col-lg-6 text-lg-center btn-wrapper">
                    <a target="_blank" rel="noopener" href="https://twitter.com/cred0"
                       class="btn btn-neutral btn-icon-only btn-twitter btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Follow us">
                        <i class="fa-brands fa-x-twitter"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://github.com/CredO-iam"
                       class="btn btn-neutral btn-icon-only btn-github btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="Star on Github">
                        <i class="fa-brands fa-github"></i>
                    </a>
                    <a target="_blank" rel="noopener" href="https://github.com/CredO-iam"
                       class="btn btn-neutral btn-icon-only btn-round btn-lg" data-toggle="tooltip"
                       data-original-title="LinkedIn">
                        <i class="fa-brands fa-linkedin"></i>
                    </a>
                </div>
            </div>
            <hr>
            <div class="row align-items-center justify-content-md-between">
                <div class="col-md-6">
                    <div class="copyright">
                        &copy; {{year}}
                        <a href="https://www.cred0.org" target="_blank" rel="noopener">CredØ - Credential Zero</a>
                    </div>
                </div>
                <div class="col-md-6">
                    <ul class="nav nav-footer justify-content-end">
                        <li class="nav-item">
                            <a href="/about" class="nav-link" target="_blank" rel="noopener">About us</a>
                        </li>
                        <li class="nav-item">
                            <a href="/mission" class="nav-link" target="_blank" rel="noopener">Our Mission</a>
                        </li>
                        <li class="nav-item">
                            <a href="mailto:info@cred0.org" class="nav-link" target="_blank" rel="noopener">Contact us</a>
                        </li>
                        <li class="nav-item">
                            <a href="https://github.com/CredO-iam/master-repo/blob/master/LICENSE.md"
                               class="nav-link" target="_blank" rel="noopener">MIT License</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data() {
    return {
      year: new Date().getFullYear()
    }
  }
};
</script>
