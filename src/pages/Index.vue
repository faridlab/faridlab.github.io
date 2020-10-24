<template>
  <q-page class="q-pa-md">
    <div class="q-gutter-md row q-my-sm">
      <div class="col"><strong class="text-h5">Personal Detail:</strong></div>
    </div>
    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Name"
          value="Farid Hidayat"
          stack-label
          filled
        />
      </div>
      <div class="col">
        <q-input
          label="Position"
          value="Senior Fullstack Developer"
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md q-my-sm row">
      <div class="col">
        <q-input
          label="About"
          value="Full Stack Developer, Mobile Developer, Technowizard, TechnoArt, Visionary Entrepreneur and Technology lover."
          autogrow
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Email"
          type="email"
          value="e.faridhidayat@gmail.com"
          stack-label
          filled
        />
      </div>
      <div class="col">
        <q-input
          label="Phone"
          type="phone"
          value="+625770900025"
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Country"
          value="Indonesia"
          stack-label
          filled
        />
      </div>
      <div class="col">
        <q-input
          label="City"
          value="South Jakarta"
          stack-label
          filled
        />
      </div>
    </div>

    <div class="q-gutter-md row q-my-sm">
      <div class="col">
        <q-input
          label="Address"
          value="Jl. Pembangunan Bawah RT.006/012 no.24"
          stack-label
          filled
        />
      </div>
      <div class="col-2">
        <q-input
          label="Postal Code"
          value="12330"
          stack-label
          filled
        />
      </div>
    </div>
    <div class="q-gutter-md row q-my-sm">
      <div class="col"><strong class="text-h5">Professional Summary:</strong></div>
    </div>

    <div class="q-gutter-md q-my-sm row">
      <div class="col">
        <q-input
          label="Summary"
          value="Farid Hidayat has 9 years of experience as an Information Technology professional especially in software development field. Currently Farid is a Product Specialist of PT. Sagara Xinix Solusitama (Sagara). Farid is highly motivated and young visionary to technology enhancement for business and economics. As business technologist, Farid has helped many institutions from government and private sector in Indonesia from initial prototype all the way to production release."
          autogrow
          stack-label
          filled
        />
      </div>
    </div>

  </q-page>
</template>

<script>
export default {
  name: 'Profile',
  data () {
    return {
      about: 'Farid Hidayat has 9 years of experience as an Information Technology professional especially in software development field. Currently Farid is a Product Specialist of PT. Sagara Xinix Solusitama (Sagara). Farid is highly motivated and young visionary to technology enhancement for business and economics. As business technologist, Farid has helped many institutions from government and private sector in Indonesia from initial prototype all the way to production release.'
    }
  }
}

</script>
