<template>
    <div>
      <div class="card my-4">
        <h5 class="card-header">Прокомментируй:</h5>
        <div class="card-body">
          <form>
            <div class="form-group">
              <textarea class="form-control" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Отправить</button>
          </form>
        </div>
      </div>
      <div class="media mb-4">
        <img class="d-flex mr-3 rounded-circle" src="http://placehold.it/50x50" alt="">
        <div class="media-body">
          <h5 class="mt-0">Дуся Иванова</h5>
          Мое очень важное мнение по данной статье. Мое очень важное мнение по данной статье. Мое очень важное мнение по данной статье. Мое очень важное мнение по данной статье. Мое очень важное мнение по данной статье.
        </div>
      </div>
    </div>
</template>

<script>
export default {
name: "Comments"
}
</script>

<style scoped>

</style>