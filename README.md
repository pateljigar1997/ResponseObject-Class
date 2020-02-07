# ResponseObject-Class






 public class ResponseObject<T>
    {
        public string Status { get; set; }
        public int Code { get; set; }
        public string Message { get; set; }
        public T Data { get; set; }
    }
