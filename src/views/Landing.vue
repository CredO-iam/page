<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-3 shape-default shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row">
                            <div class="col-lg-6">
                                <h1 class="display-4  text-white">Rethinking IAM from the ground up
                                    <span>without compromise</span>
                                </h1>
                                <p class="lead  text-white">Built for developers and security teams. <br>
                                  No black boxes — full visibility and full control. <br>
                                  Keep your credentials on your terms — self-hosted or SaaS, without vendor lock-in.</p>
                                <div class="btn-wrapper">
                                    <base-button tag="a"
                                                 href="https://demo.cred0.org/saas"
                                                 class="mb-3 mb-sm-0"
                                                 type="info"
                                                 icon="fa fa-code">
                                        Show demo
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-check-bold" type="primary" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-primary text-uppercase">Download image</h6>
                                    <p class="description mt-3">Download, run, and own your CredØ in seconds.
                                      A ready-to-use Docker image for quick on-premise deployment.
                                      No cloud, no headaches — everything runs locally, under your control.
                                    </p>
                                    <div>
                                        <badge type="primary" rounded>SelfHosted</badge>
                                        <badge type="primary" rounded>In-Docker</badge>
                                        <badge type="primary" rounded>No-Cloud</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="primary" class="mt-4">
                                        DOWNLOAD
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-istanbul" type="success" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-success text-uppercase">SaaS Easy</h6>
                                    <p class="description mt-3">Start using CredØ in minutes — no installation required.
                                      Register your OAuth client in our shared cloud instance and you’re good to go.
                                      Free tier available — limited clients, unlimited simplicity.</p>
                                    <div>
                                        <badge type="success" rounded>cloud</badge>
                                        <badge type="success" rounded>free</badge>
                                        <badge type="success" rounded>easy</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Start using
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <icon name="ni ni-planet" type="warning" rounded class="mb-4">
                                    </icon>
                                    <h6 class="text-warning text-uppercase">SaaS Platform Pro</h6>
                                    <p class="description mt-3">Your instance. Fully under your control.
                                      A dedicated cloud environment with full customization and unlimited clients.
                                      Connect your own on-premise adapter and tailor everything to your needs.</p>
                                    <div>
                                        <badge type="warning" rounded>Power</badge>
                                        <badge type="warning" rounded>Full-Control</badge>
                                    </div>
                                    <base-button tag="a" href="#" type="warning" class="mt-4">
                                        Try now
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="warning"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">Support CredØ — and digital sovereignty.</h3>
                                <p class="lead text-white mt-3">We build open tools to put identity infrastructure back in your hands.
                                  Your support helps keep the core free, transparent, and independent.</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="/support"
                                             type="white" block size="lg">
                                    Support us!
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>
        <section class="section section-shaped my-0 overflow-hidden">
            <div class="shape shape-style-3 bg-gradient-default shape-skew">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
            </div>
            <div class="container pt-lg pb-300">
                <div class="row text-center justify-content-center">
                    <div class="col-lg-10">
                      <h2 class="display-3 text-white">We'd love to hear from you</h2>
                      <p class="lead text-white">Whether you have questions, feedback, or ideas — reach out. <br>
                        We’re building CredØ for developers like you.</p>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-lg-0 section-contact-us">
            <div class="container">
                <div class="row justify-content-center mt--300">
                    <div class="col-lg-8">
                        <card gradient="secondary" shadow body-classes="p-lg-5">
                            <h4 class="mb-1">Are you interested in CredØ?</h4>
                            <p class="mt-0">We are here to help you with any questions or
                                concerns you may have.</p>
                            <base-input class="mt-5"
                                        alternative
                                        placeholder="Your name"
                                        addon-left-icon="ni ni-user-run">
                            </base-input>
                            <base-input alternative
                                        placeholder="Email address"
                                        addon-left-icon="ni ni-email-83">
                            </base-input>
                            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Type a message..."></textarea>
                            </base-input>
                            <base-button type="default" round block size="lg">
                                Send Message
                            </base-button>
                        </card>
                    </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>
export default {
  name: "home",
  components: {}
};
</script>
