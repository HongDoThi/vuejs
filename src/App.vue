<template>
  <div class="container">
    <div class="row">
      <div class="col-8 offset-2">
        <form action class="form-group">
          <h3>From section Vuejs</h3>
          <div class="form-group">
            <label for="exampleInputEmail1">Email</label>
            <input
              type="text"
              class="form-control"
              id="exampleInputEmail1"
              aria-describedby="emailHelp"
              placeholder="Enter email"
             v-model="email"
            />
          </div>
          <div class="form-group">
            <label for="exampleInputEmail1">Password</label>
            <input
              type="password"
              class="form-control"
              id="exampleInputEmail1"
              aria-describedby="emailHelp"
              placeholder="Enter email"
            />
          </div>
          <div class="form-group">
            <label for="exampleInputEmail1">Age</label>
            <input
              type="number"
              class="form-control"
              id="exampleInputEmail1"
              aria-describedby="emailHelp"
              placeholder="Enter email"
            />
          </div>
          <div class="form-group">
            <label for="exampleInputEmail1">Message</label>
            <textarea name id cols="90" rows="10"></textarea>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" value id="defaultCheck1" />
            <label class="form-check-label" for="defaultCheck1">Send mail</label>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" value id="defaultCheck2" disabled />
            <label class="form-check-label" for="defaultCheck2">Send information</label>
          </div>
          <div class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="exampleRadios"
              id="exampleRadios1"
              value="option1"
              checked
            />
            <label class="form-check-label" for="exampleRadios1">Male</label>
          </div>
          <div class="form-check">
            <input
              class="form-check-input"
              type="radio"
              name="exampleRadios"
              id="exampleRadios1"
              value="option1"
              checked
            />
            <label class="form-check-label" for="exampleRadios1">Female</label>
          </div>
          <label for>Property</label>
          <select name id class="form-control">
            <option value></option>
          </select>
          <button class="btn btn-primary mt-5">Submit</button>
        </form>
        <div class="row">
          <div class="col-8 offset-2">
            <div class="panel panel-default">
              <div class="panel-heading">Your data</div>
              <div class="panel-body">
                <p>Mail: {{email}}}</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    email: '';
   
  }
};
</script>

<style>
</style>
